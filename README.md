# Exp 2 : ORACLE-VM-VIRTUAL-BOX-INSTALLATION--
## AIM:
To install Oracle VM VirtualBox, a free and open-source hosted hypervisor, on a computer system,enabling the creation and management of virtual machines for running multiple operating systems on a single host machine
### EQUIPMENTS REQUIRED:
    • Hardware: PCs
    • Software: Oracle VM ware  , CENT OS 
    • A system with Oracle VM VirtualBox installed.  At least 4 GB RAM and 20 GB free disk space.
    •   Kali Linux ISO image, which can be downloaded from the official website.

## Procedure:
#### Step 1: Download VirtualBox
 Go to the VirtualBox official website: VirtualBox Downloads  Choose the appropriate version for your operating system:
 Windows hosts (for Windows users)
 macOS hosts (for Mac users)
 Linux distributions (for Linux users)
#### Step 2: Install VirtualBox (Windows/macOS)
For Windows:
    1. Open the downloaded installer ( VirtualBox-x.x.x-xxxx-Win.exe ).
    2. Follow the setup wizard:  Click Next.
 Select the installation location (default is recommended).
  Choose the components you want to install and click Next.
 The installer may show a warning about network interfaces; allow it to proceed by clicking Yes.
    3. Click Install and allow the process to complete.
#### Step 3: Verify the Installation
    1. Launch VirtualBox from the desktop or start menu.
    2. The VirtualBox Manager should open, showing options to create and manage virtual machines.
### Step-by-Step Installation Guide:
#### Step 1: Download Kali Linux ISO
    1. Go to the Kali Linux download page.
    2. Download the Kali Linux ISO file.
 Choose between 32-bit or 64-bit depending on your system (most systems are 64-bit).  Download the Installer version for a full installation.
#### Step 2: Open Oracle VM VirtualBox
    1. Launch VirtualBox on your computer.
    
<img width="932" height="585" alt="image" src="https://github.com/user-attachments/assets/3219153c-9da1-430a-8ba8-c4ec04d7d104" />



#### Step 3: Create a New Virtual Machine
    1. In VirtualBox, click on the New button to create a new virtual machine.
    2. Name and Type Settings:
 Name: Give a name like "Kali Linux".
 Type: Select Linux.
 Version: Select Debian (64-bit) or Debian (32-bit) depending on the ISO version you downloaded.
    3. Click Next to proceed.
#### Step 4: Allocate Memory (RAM)
    1. Choose how much RAM to allocate to your virtual machine.
  Recommended: At least 2 GB (2048 MB) for Kali Linux, or 4 GB if possible.
    2. Click Next.
#### Step 5: Create a Virtual Hard Disk
    1. Select Create a virtual hard disk now.
    2. Click Create.
#### Step 6: Select Hard Disk File Type
    1. Choose VDI (VirtualBox Disk Image).
    2. Click Next.
#### Step 7: Storage on Physical Hard Disk
    1. Select Dynamically allocated (so the disk will grow as needed).
    2. Click Next.
#### Step 8: Allocate Storage Space
    1. Set the hard disk size. Kali Linux requires at least 20 GB of storage.
  You can increase this if you plan to install many additional tools later.
    2. Click Create.
#### Step 9: Configure Kali Linux ISO
    1. Select the VM from the list in VirtualBox and click Settings.
    2. Navigate to Storage from the side menu.
    3. Under Controller: IDE, click the Empty CD icon.
    4. On the right, click the CD icon next to Optical Drive and choose Choose a disk file....
    5. Locate and select the Kali Linux ISO you downloaded.
    6. Click OK.
#### Step 10: Start the Virtual Machine
    1. In VirtualBox, click Start to boot up your Kali Linux virtual machine.
    
<img width="933" height="588" alt="image" src="https://github.com/user-attachments/assets/01cc66db-3ec8-43ec-b818-b8ba014d8116" />




#### Step 11: Begin Kali Linux Installation
    1. The VM will now boot from the ISO. You’ll see a boot menu.  Select Graphical Install and press Enter.


#### Step 12: Select Language and Region
    1. Choose your language, location, and keyboard layout.  These can be configured to your preference.
    2. Click Continue after each selection.
#### Step 13: Configure the Network
    1. You’ll be prompted to configure the network.
  Enter a hostname for your system (e.g., kali).
  You can leave the domain name empty if you don’t need to set up a domain.
#### Step 14: Set Up Users and Passwords
    1. Create a root password for the administrator account.
  Choose a strong password and re-enter it for confirmation.
#### Step 15: Partition Disks
    1. Choose Guided - use entire disk for simplicity (recommended for beginners).
    2. Select the virtual disk you created earlier.
    3. Choose All files in one partition.
    4. Finish partitioning and confirm to write the changes to disk.
#### Step 16: Install the System
    1. The installer will now copy files and install Kali Linux. This may take several minutes.
#### Step 17: Install GRUB Bootloader
    1. When prompted to install the GRUB bootloader, choose Yes.
    2. Select the virtual hard disk as the location to install GRUB.
#### Step 18: Complete Installation
    1. After the installation is complete, click Continue to reboot the virtual machine.
#### Step 19: Login to Kali Linux
    1. Once the machine reboots, you’ll be presented with a login screen.
    2. Log in using the root account and the password you set earlier.

## EXPECTED OUTPUT

<img width="1918" height="1020" alt="image" src="https://github.com/user-attachments/assets/43b5ca22-f8aa-4066-a565-c9c041c58e16" />



# .sh method

## PROGRAM
#### Shell script to add two numbers:
<img width="452" height="365" alt="image" src="https://github.com/user-attachments/assets/4b88ab5f-ab58-43a8-9b57-94a817e3dc4a" />




## EXPECTED OUTPUT

<img width="262" height="173" alt="Screenshot 2025-08-29 093743" src="https://github.com/user-attachments/assets/09b785be-dc6e-4ffd-9e45-149551df8b3d" />



## CHMOD METHOD

<img width="235" height="60" alt="Screenshot 2025-08-29 093857" src="https://github.com/user-attachments/assets/ea31c6f4-f502-461b-9381-4031b06124e7" />



# TERMINAL METHOD

<img width="437" height="376" alt="Screenshot 2025-08-29 092809" src="https://github.com/user-attachments/assets/513d0b74-8cc8-44ba-8e87-4ebaa2e38bac" />



# .c METHOD

<img width="237" height="49" alt="Screenshot 2025-08-29 095307" src="https://github.com/user-attachments/assets/fc79f62d-98bf-4475-b492-3fd5c2cf2911" />
<br>
<img width="557" height="382" alt="image" src="https://github.com/user-attachments/assets/e9a9553f-26fa-4bb9-9d28-f6971d4c7e05" />
<br>

<img width="247" height="52" alt="Screenshot 2025-08-29 095314" src="https://github.com/user-attachments/assets/e1579ada-6519-489c-b209-8e9a2018e9a7" />
<br>
<img width="256" height="100" alt="Screenshot 2025-08-29 095321" src="https://github.com/user-attachments/assets/88b3094e-e438-48ce-98f4-f3ee8422bfa4" />

# LINUX COMMANDS

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls

<img width="786" height="95" alt="Screenshot 2025-08-25 083039" src="https://github.com/user-attachments/assets/02bf62c2-c948-4347-a459-d5a99fc25fcb" />

### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="187" height="81" alt="Screenshot 2025-08-25 083048" src="https://github.com/user-attachments/assets/9caed99a-69f8-492c-a0ac-efa7654c0539" />

### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="860" height="118" alt="Screenshot 2025-08-25 083259" src="https://github.com/user-attachments/assets/63e87d5e-a810-4b1b-958d-49280ac81d49" />

### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="786" height="134" alt="Screenshot 2025-08-25 083320" src="https://github.com/user-attachments/assets/b5312fd8-dae0-4000-ac75-5ccd39f934df" />

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="256" height="148" alt="image" src="https://github.com/user-attachments/assets/c6a5f4e7-1c0a-4efa-9f57-bd74d63476d4" />

### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="243" height="90" alt="image" src="https://github.com/user-attachments/assets/8281a04c-4004-49b8-bd23-d83bb15c08c7" />
<br>
<img width="252" height="97" alt="image" src="https://github.com/user-attachments/assets/f6290e0a-a029-4da5-b9fb-c66fe87a6f79" />

### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="253" height="142" alt="image" src="https://github.com/user-attachments/assets/ee168117-6988-4aaf-bda8-6bb75ba0ad7a" />

### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="261" height="56" alt="image" src="https://github.com/user-attachments/assets/20ac0a42-daf9-4824-9062-1eacdedda629" />

### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="207" height="93" alt="image" src="https://github.com/user-attachments/assets/d2b0279d-d941-41c0-a8bb-567bb7263a1e" />

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="252" height="292" alt="image" src="https://github.com/user-attachments/assets/7b599f7e-3436-4396-9822-71eecb742321" />

## RESULT
Thus, this experiment helped in understanding the fundamentals of Linux commands and Bash scripting for automation and system management.
