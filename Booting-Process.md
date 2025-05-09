The booting process refers to the sequence of operations a computer system performs to load the operating system into memory and initiate normal operations. It is a fundamental procedure required for system startup.


## **Booting Process Steps**

###  **Power Supply (SMPS – Switched Mode Power Supply)**

* Converts AC (Alternating Current) from the wall outlet into regulated DC (Direct Current) used by internal components.
* Supplies power to the motherboard, CPU, drives, and other peripherals.
* Essential for all types of computing systems, including gaming PCs and workstations that require high wattage.


### **BIOS (Basic Input/Output System)**

* Firmware stored in non-volatile memory (ROM/Flash).
* Executes immediately after power is supplied.

  **Key Functions:**

  * **POST (Power-On Self Test):** Verifies hardware integrity (RAM, CPU, storage, keyboard, etc.).
  * **Hardware Initialization:** Prepares system devices for OS control.
  * **Boot Device Detection:** Identifies available bootable media based on the user-defined boot order.



### **Bootloader**

* A small program responsible for loading the operating system kernel into memory.

  **Examples:**

  * **GRUB** (Linux)
  * **Windows Boot Manager** (Windows)

  **Responsibilities:**

  * Loads the OS kernel and transfers control.
  * May present a boot menu if multiple OS installations or kernel versions are available.



###  **Kernel Loading**

* The selected operating system's kernel is loaded into RAM.
* The kernel manages critical system resources and begins system initialization.

  **Functions Include:**

  * Memory and process management
  * Hardware abstraction
  * Device driver loading
  * Mounting root file systems



### **Init System / systemd**

* The kernel launches the first user-space process.

  **Types:**

  * Traditional: `init`
  * Modern (Linux): `systemd`

  **Responsibilities:**

  * Starts essential system services (e.g., network, logging, sound)
  * Sets up system targets (multi-user mode, graphical interface, etc.)



### **Login Manager**

* Manages user authentication and session startup.

  **Types:**

  * **Graphical (GUI):** e.g., GDM, LightDM, SDDM
  * **Text-based (CLI):** Presents a login prompt in terminal mode

  **Responsibilities:**

  * Authenticates users via username and password
  * Launches desktop environments or shell sessions based on configuration


![img](https://github.com/user-attachments/assets/f34b7ff3-3928-41ae-9cd4-e3e14a7172c5)