An IP address is a unique identifier assigned to each device on a network. It allows devices to communicate with one another. 


## **Types of IP Addresses**

* **IPv4 (Internet Protocol version 4)**
* **IPv6 (Internet Protocol version 6)**



## **IPv4 (Internet Protocol version 4)**

### **Overview**

* **Bit Size**: 32-bit address
* **Structure**: 4 sections (octets), each 8 bits
* **Range per Section**: 0–255
* **Address Range**: `0.0.0.0` to `255.255.255.255`
* **Total Addresses**: 2³² = 4,294,967,296

### **IPv4 Address Structure**

* **Fixed Length**: 32 bits
* **Divided into 4 octets** (8 bits each)
* **Separation**: Dots (e.g., `192.168.1.1`)
* **Value Range per Octet**: 0 to 255 (8-bit binary max is `11111111`, i.e., 255)

#### **Example: Binary to Decimal Conversion**

**Binary IP**: `11000000.10101000.00000001.00000001`

**Step 1: Break into Octets**

* Octet 1: `11000000`
* Octet 2: `10101000`
* Octet 3: `00000001`
* Octet 4: `00000001`

**Step 2: Convert to Decimal**

* 11000000 = 192
* 10101000 = 168
* 00000001 = 1
* 00000001 = 1

**Resulting IPv4 Address**: `192.168.1.1`



## **Classful and Classless IP Addressing**

### **Classful IP Addressing**

IP addresses are grouped into classes based on predefined ranges.

#### **Class A**

* **Purpose**: Large networks (e.g., governments, ISPs)
* **Binary Range**: Starts with `0`
* **IP Range**: `0.0.0.0` to `127.255.255.255`
* **Structure**: `N.H.H.H`

  * Network Bits: 7
  * Host Bits: 24
* **Networks**: 2⁷ – 2 = 126
* **Hosts per Network**: 2²⁴ – 2 = 16,777,214

#### **Class B**

* **Purpose**: Medium-sized organizations
* **Binary Range**: Starts with `10`
* **IP Range**: `128.0.0.0` to `191.255.255.255`
* **Structure**: `N.N.H.H`

  * Network Bits: 14
  * Host Bits: 16
* **Networks**: 2¹⁴ = 16,384
* **Hosts per Network**: 2¹⁶ – 2 = 65,534

#### **Class C**

* **Purpose**: Small organizations
* **Binary Range**: Starts with `110`
* **IP Range**: `192.0.0.0` to `223.255.255.255`
* **Structure**: `N.N.N.H`

  * Network Bits: 21
  * Host Bits: 8
* **Networks**: 2²¹ = 2,097,152
* **Hosts per Network**: 2⁸ – 2 = 254

#### **Class D**

* **Purpose**: Multicast (e.g., streaming services)
* **Binary Range**: Starts with `1110`
* **IP Range**: `224.0.0.0` to `239.255.255.255`
* **Note**: No host/network division

#### **Class E**

* **Purpose**: Experimental and future use
* **Binary Range**: Starts with `1111`
* **IP Range**: `240.0.0.0` to `255.255.255.255`
* **Note**: Reserved for research/development



## **Private vs Public IP Addresses**

### **Private IP Addresses**

* Used within local networks (LAN)
* Not routable on the internet
* **Free to use**
* **Private Ranges**:

  * Class A: `10.0.0.0` – `10.255.255.255`
  * Class B: `172.16.0.0` – `172.31.255.255`
  * Class C: `192.168.0.0` – `192.168.255.255`

### **Public IP Addresses**

* Used for internet communication
* **Assigned by ISPs**
* **Not free**
* **Public Ranges**:

  * Class A: `1.0.0.0` – `126.255.255.255`
  * Class B: `128.0.0.0` – `191.255.255.255`
  * Class C: `192.0.0.0` – `223.255.255.255`



## **Basic IP Assignment Rules**

* Avoid assigning:

  * **`0.0.0.0`** (used for default routing)
  * **IPs with no host bits enabled** (e.g., `1.0.0.0`)
  * **IPs with all host bits enabled** (e.g., `1.255.255.255`)
* **Ensure uniqueness** within a network