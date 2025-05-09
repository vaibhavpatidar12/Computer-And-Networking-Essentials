## **TCP/IP Model (Transmission Control Protocol/Internet Protocol)**

The TCP/IP model is a concise, practical framework used to describe and implement modern internet networking. Unlike the OSI model, which has seven layers, the TCP/IP model is composed of **four layers**, each corresponding roughly to specific OSI layers. TCP/IP is the foundation of the internet and governs how data is packetized, addressed, transmitted, routed, and received.

### **1. Application Layer**

This top layer of the TCP/IP model combines the OSI model’s Application, Presentation, and Session layers. It provides end-user services and interfaces directly with software applications to enable communication over the network.

**Common Application Layer Protocols:**

* **HTTP/HTTPS** – Web browsing
* **FTP** – File transfer
* **SMTP/POP3/IMAP** – Email communication
* **DNS** – Resolves domain names to IP addresses
* **Telnet/SSH** – Remote terminal access

### **2. Transport Layer**

This layer corresponds to the Transport Layer of the OSI model. It ensures reliable or best-effort data delivery between devices. It uses ports to distinguish multiple applications on the same device.

**Key Protocols:**

* **TCP (Transmission Control Protocol):** Reliable, connection-oriented (e.g., web browsing, email)
* **UDP (User Datagram Protocol):** Faster, connectionless (e.g., video streaming, DNS queries)

### **3. Internet Layer**

Equivalent to the OSI's Network Layer, the Internet Layer handles logical addressing, routing, and packet delivery across multiple networks.

**Core Protocols:**

* **IP (Internet Protocol):** Routing and addressing (IPv4 and IPv6)
* **ICMP (Internet Control Message Protocol):** Error reporting and diagnostics
* **ARP (Address Resolution Protocol):** Resolves IP addresses to MAC addresses

### **4. Network Access Layer (Link Layer)**

This layer encompasses the OSI’s Data Link and Physical layers. It handles the physical transmission of data over the hardware, as well as addressing and error detection at the frame level.

**Technologies and Protocols:**

* **Ethernet**
* **Wi-Fi**
* **PPP (Point-to-Point Protocol)**
* **MAC addressing**

### **Comparison: OSI vs TCP/IP Layers**


![img](https://media.geeksforgeeks.org/wp-content/uploads/20230417045622/OSI-vs-TCP-vs-Hybrid-2.webp)
