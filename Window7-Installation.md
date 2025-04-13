
# Installation of Window-7

Here's a **step-by-step guide to installing Windows 7** on a Virtual-Box

win 7  bit iso - [https://tech-latest.com/download-windows-7-iso/](https://tech-latest.com/download-windows-7-iso/)

### Steps 

Step 1:
1. Install the window 7 ultimate iso from archive website 
![alt text](1.1.png)

2. Virtual Box Setup -
3. Click **New**.
![alt text](1.png)

Step 2:  Name it something like `Windows-7`.
  - - Set:
    - **Type:** Microsoft Windows
    - **Version:** Windows 7 (32-bit or 64-bit depending on your ISO)
    - Click **Next**.
![alt text](2.png)



Step 3: Allocate RAM
- Minimum: 4096 MB (4 GB) 
- Set Boot Order 
![alt text](3.png)

![alt text](4.png)



Mount Windows 7 ISO
1. Select your new VM, click **Settings**. 
2. Go to **Storage**.
3. Under **Controller: IDE**, click the empty disc icon.
4. On the right, click the disc icon and choose **Choose a disk file**.
5. Select your **Windows 7 ISO file**.
6. Click **OK**.
![alt text](5.png)

Step 4: Create a Virtual Hard Disk
- Choose **Create a virtual hard disk now**.
-  Choose format **VDI (VirtualBox Disk Image)**.
![alt text](6.png)

- Choose **Dynamically allocated**.
-  Set size: at least **40 GB**.
-  Click **Create**.
![alt text](7.png)

![alt text](8.png)

![alt text](9.png)

 Step 5: Start the VM
1. Select the VM and click **Start**.
2. It will boot from the ISO.
Choose your preferred **language**, **time and currency format**, and **keyboard or input method**.
![alt text](10.png)

![alt text](11.png)

Accept license > **Next**.
![alt text](12.png)

Choose **Custom (Advanced)**.
![alt text](13.png)

![alt text](14.png)

Select the virtual hard disk > **Next**.
![alt text](15.png)

![alt text](16.png)

![alt text](17.png)

![alt text](18.png)

Step 6: Complete Setup
1. Enter a username and computer name.
![alt text](19.png)


Set a password (optional).
![alt text](20.png)

Enter product key (or skip to activate later).
![alt text](21.png)

![alt text](22.png)

Choose update settings, set time, etc.
![alt text](23.png)

![alt text](24.png)

![alt text](25.png)

 Step 7: Install VirtualBox Guest Additions (Optional but recommended)
1. While Windows is running, click **Devices > Insert Guest Additions CD image…** in VirtualBox menu.
![alt text](26-install-driver.png)

2. Open the virtual CD inside Windows and run the installer.   
![alt text](27.png)

![alt text](28.png)

![alt text](29.png)

![alt text](30.png)

![alt text](31.png)

![alt text](32.png)


![alt text](33.png)

2. Reboot when done — this improves graphics, enables shared clipboard, etc.
![alt text](34.png)

Done! 🎉 You now have a working **Windows 7 virtual machine**.