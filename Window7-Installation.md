# Install Windows 7 on VirtualBox

This guide walks you through installing **Windows 7** in a **VirtualBox** environment. Whether you're testing legacy applications or just exploring, follow these steps for a smooth setup.


## 📥 Requirements

* **Windows 7 ISO**: Download a 32-bit or 64-bit version from:
  [Download Windows 7 ISO](https://tech-latest.com/download-windows-7-iso/)

* **VirtualBox**: Ensure VirtualBox is installed on your host system.


## Installation Steps

### Step 1: Download & Launch VirtualBox

1. Download the **Windows 7 ISO** from the link above.
2. Launch **VirtualBox**.
3. Click **New** to start creating a new virtual machine.

![Step 1](https://github.com/user-attachments/assets/048c3a67-a68f-4c23-905b-6d0177ff718b)



### Step 2: Create the Virtual Machine

* **Name**: e.g., `Windows-7`
* **Type**: Microsoft Windows
* **Version**: Windows 7 (choose 32-bit or 64-bit accordingly)
  Click **Next**.

![Step 2](https://github.com/user-attachments/assets/f4e52604-4ae0-444d-968e-52f6e54b490d)



### Step 3: Allocate System Resources

* **Memory (RAM)**: Minimum 4096 MB (4 GB)
* **Boot Order**: Make sure the optical drive is listed first.

![Memory Setup](https://github.com/user-attachments/assets/7a504212-d7ab-4e83-8bce-43e2a563b690)



### Step 4: Mount the Windows 7 ISO

1. Select the newly created VM and click **Settings**.
2. Navigate to **Storage**.
3. Under **Controller: IDE**, click the empty disc icon.
4. On the right, click the disc symbol → **Choose a disk file**.
5. Select your **Windows 7 ISO**.
6. Click **OK**.

![Mount ISO](https://github.com/user-attachments/assets/acda4436-c631-4728-870e-1f9e44ab839b)



### Step 5: Create a Virtual Hard Drive

* Choose: **Create a virtual hard disk now**
* File type: **VDI (VirtualBox Disk Image)**
* Storage: **Dynamically allocated**
* Size: At least **40 GB**

Click **Create**.

![Virtual Disk](https://github.com/user-attachments/assets/c5506ec2-fdb2-48ba-b76b-7bd8777bfe66)



### Step 6: Start the Virtual Machine

1. Select the VM and click **Start**.
2. The machine will boot from the ISO.
3. Choose language, time, and keyboard layout.

![Install Start](https://github.com/user-attachments/assets/6568ad15-a812-4b56-aeb1-0b22427e8c11)

4. Accept the license agreement and click **Next**.
5. Choose **Custom (Advanced)** installation.

![Custom Install](https://github.com/user-attachments/assets/fc7c1fa9-d4c7-48c5-8e56-c8c81c53c0b5)

6. Select the virtual hard disk and click **Next**.



### Step 7: Complete Windows Setup

1. Enter a **username** and **computer name**.
2. Optionally set a **password**.
3. Enter the **product key** or skip it for later activation.
4. Choose **update settings**, configure **date & time**, and set up **networking**.

![Setup](https://github.com/user-attachments/assets/b05aaa15-f38a-41a5-957f-ab7c19a80220)



### Step 8: (Optional) Install Guest Additions

For better performance and features like shared clipboard and full-screen mode:

1. With the VM running, go to **Devices > Insert Guest Additions CD image**.
2. Inside the VM, open the virtual CD and run the installer.
3. Follow the installation steps and **reboot** the VM when prompted.

![Guest Additions](https://github.com/user-attachments/assets/aea53ecb-e271-4f8d-a86c-224425915043)