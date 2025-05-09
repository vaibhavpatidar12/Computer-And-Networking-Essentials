# **Subnet Mask / Netmask / Network Mask**

A **Subnet Mask** (also called **Netmask** or **Network Mask**) is used in IP networking to divide an IP address into **network** and **host** portions. It tells which part of the IP address identifies the **network** and which part identifies the **device (host)**.



## **Network Mask Structure**

* **Total Bits**: 32 bits (just like an IPv4 address)
* **Sections**: 4 sections (octets)
* **Bits per Section**: 8 bits each
* **Representation**: Binary or Decimal (e.g., `11111111.00000000.00000000.00000000` = `255.0.0.0`)
* **Binary Pattern**:

  * **Network part**: All bits are `1`
  * **Host part**: All bits are `0`



## **Subnet Masks by IP Class**

### **Class A**

* **Example IP**: `1.0.0.1`
* **Structure**: `N.H.H.H` (Network.Host.Host.Host)
* **Binary Mask**: `11111111.00000000.00000000.00000000`
* **Decimal Mask**: `255.0.0.0`

### **Class B**

* **Example IP**: `128.0.0.1`
* **Structure**: `N.N.H.H` (Network.Network.Host.Host)
* **Binary Mask**: `11111111.11111111.00000000.00000000`
* **Decimal Mask**: `255.255.0.0`

### **Class C**

* **Example IP**: `192.0.0.1`
* **Structure**: `N.N.N.H` (Network.Network.Network.Host)
* **Binary Mask**: `11111111.11111111.11111111.00000000`
* **Decimal Mask**: `255.255.255.0`


## **Purpose of a Subnet Mask**

* **Identifies** how many bits are used for the network and how many for hosts.
* **Helps routers** understand where to send packets.
* **Enables subnetting**, which breaks large networks into smaller, manageable parts.
