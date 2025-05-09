## **OSI Model (Open Systems Interconnection)**
The OSI model serves as a standard reference framework for understanding and designing communication systems. It provides a clear separation of functionality between layers, allowing for interoperability between different devices and network architectures.



### **7. Application Layer**

The Application Layer is the topmost layer of the OSI model. It enables end users to interact with the network and access services such as file sharing, email, and web browsing. This layer provides services and interfaces to user applications, facilitating data exchange and enabling network communication.

**Examples of Application Layer protocols include:**

* **HTTP (Hypertext Transfer Protocol):** Port 80 (HTTP), Port 443 (HTTPS)
* **FTP (File Transfer Protocol):** Port 20 (FTP Data), Port 21 (FTP Control)
* **SMTP (Simple Mail Transfer Protocol):** Port 25
* **DNS (Domain Name System):** Port 53
* **SSH (Secure Shell):** Port 22
* **Telnet:** Port 23
* **POP3 (Post Office Protocol):** Port 110
* **IMAP (Internet Message Access Protocol):** Port 143



### **6. Presentation Layer**

The Presentation Layer is responsible for translating data from the Application Layer into a format suitable for network transmission. It handles data encryption/decryption, compression/decompression, and formatting.

**Examples of Presentation Layer protocols include:**

* **JPEG (Joint Photographic Experts Group):** Image compression
* **MPEG (Moving Picture Experts Group):** Video and audio compression
* **ASCII (American Standard Code for Information Interchange):** Text encoding
* **MIME (Multipurpose Internet Mail Extensions):** Formatting emails with multimedia
* **XDR (External Data Representation):** Cross-platform data exchange



### **5. Session Layer**

The Session Layer manages communication sessions between two devices. It establishes, maintains, and terminates sessions and provides synchronization and checkpointing to ensure reliable data exchange.

**Examples of Session Layer protocols include:**

* **L2TP (Layer 2 Tunneling Protocol):** Used in VPNs, often with IPsec
* **NetBIOS (Network Basic Input/Output System):** Enables file and print sharing over LANs
* **PPTP (Point-to-Point Tunneling Protocol):** VPN protocol, often paired with MS-CHAP
* **PAP (Password Authentication Protocol):** Basic authentication method, though less secure



### **4. Transport Layer**

The Transport Layer ensures reliable data transmission between endpoints. It provides error detection, flow control, and ensures that data arrives in the correct sequence.

Key protocols in this layer:

* **TCP (Transmission Control Protocol):** Reliable, connection-oriented communication
* **UDP (User Datagram Protocol):** Fast, connectionless communication with minimal overhead



### **3. Network Layer**

The Network Layer receives data from the Transport Layer and adds a header containing source and destination logical addresses (e.g., IP addresses). It determines the optimal path for data using routing protocols.

**Examples of Network Layer protocols include:**

* **IP (Internet Protocol):** Logical addressing, routing, fragmentation
* **ICMP (Internet Control Message Protocol):** Error reporting and diagnostics
* **ARP (Address Resolution Protocol):** Maps IP addresses to MAC addresses
* **RIP (Routing Information Protocol):** Determines routing paths using distance vectors



### **2. Data Link Layer**

The Data Link Layer manages access to the physical medium and handles error detection and correction. It uses MAC addresses to direct frames to the correct destination and is the layer where switches operate.

**Examples of Data Link Layer protocols include:**

* **Ethernet (IEEE 802.3)**
* **Wi-Fi (IEEE 802.11)**
* **PPP (Point-to-Point Protocol)**
* **HDLC (High-Level Data Link Control)**



### **1. Physical Layer**

The Physical Layer transmits raw bits over a physical medium, such as copper wire or fiber optic cable. It defines the electrical, mechanical, and procedural specifications for data transmission.

**Examples of Physical Layer technologies include:**

* **Fiber optic cables** (various standards)
* **DSL (Digital Subscriber Line)** technologies

![osi](https://miro.medium.com/v2/resize:fit:720/format:webp/1*ZGnXoisgbx3EKeKtQyMVFg.png)
