## Ex.3(A-C) Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands

## Aim:

To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox

## Aim:

To install and configure Oracle VM VirtualBox.

## Pre-requisites:

Machine with Internet access
Minimum 4 GB RAM
Sufficient storage space

## Steps:

Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site
Download installer for your OS (Windows/macOS/Linux).
Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next.
Choose Installation Options → Click Next.
Accept Network Interface Warning → Click Yes.
Click Install.
Finish Installation and Launch VirtualBox.
Configure VirtualBox:

Open VirtualBox.
Click New → Name VM → Select Type (Linux/Windows) and Version.
Allocate:
Minimum 2 GB RAM
Create Virtual Hard Disk (20 GB recommended).
Start Virtual Machine and provide ISO to install OS.

## Result:

Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux

## Aim:

To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:

Oracle VM VirtualBox Installed
4 GB RAM and 20 GB Storage Minimum
Kali Linux ISO image

## Steps:

Download Kali Linux ISO:

Visit Kali Linux Official Site
Download 64-bit ISO (Installer version).
Create a New Virtual Machine:

Open VirtualBox → Click New.
Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB).
Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image).
Choose Dynamically allocated.
Set Disk size to 20 GB or more.
Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
Start Installation:

Boot Virtual Machine → Choose Graphical Install.
Set Language, Region, Keyboard.
Configure Network → Set Hostname (e.g., kali).
Set root password.
Disk Partitioning: Use entire disk → All files in one partition.
Install System → Install GRUB Bootloader → Finish Installation.
Login to Kali Linux:

Use root credentials.
(Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.

## Snapshots:

AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox 

![image](https://github.com/user-attachments/assets/12903464-4b49-4bcd-9ac6-85e08d080285)


Snapshot 2: Kali Running in Virtual 

![image](https://github.com/user-attachments/assets/27c05f01-edf7-470f-b43a-adf8ad2ba7fb)


## Result:

Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali

## About Linux:

Open-source operating system.
Kernel manages communication between hardware and software.
Commands are case-sensitive.

## Linux Commands:

ls Command

The ls command is used to display a list of content of a directory.

## Syntax:

ls

![image](https://github.com/user-attachments/assets/3acee592-454f-46fa-9ea9-4f2753a48cba)


pwd Command

The pwd command is used to display the location of the current working directory.

## Syntax:

pwd

![image](https://github.com/user-attachments/assets/29ba05ee-074b-4d01-b52c-c90b3f1f7f37)


3.mkdir Command

The mkdir command is used to create a new directory under any directory.

## Syntax:

mkdir <directory_name>

![image](https://github.com/user-attachments/assets/b4e85b85-f518-450c-8d9b-dfe4e2283bb7)


rmdir Command

The rmdir command is used to delete a directory.

## Syntax:

rmdir <directory_name>

![image](https://github.com/user-attachments/assets/811b56e2-0405-464d-b71f-b1804d407aef)

cd Command The cd command is used to change the current directory

## Syntax:

cd <directory_name>

![image](https://github.com/user-attachments/assets/967154d0-9079-4778-bf10-a8f74800e35c)

## cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

## Syntax:
cat [options] [file_name]

![image](https://github.com/user-attachments/assets/1e2e1849-0066-4a8d-a286-e221a0fada85)

![image](https://github.com/user-attachments/assets/ee4823b9-3ce3-48c6-bf0b-9f420d1115df)

cp Command

The cp command is used to copy a file or directory.

## Syntax:

cp [source] [destination]

![image](https://github.com/user-attachments/assets/62e7ff55-d2f3-4fb4-ba5d-67c0f465e776)

![image](https://github.com/user-attachments/assets/3cc3d9d6-a4b7-4247-b959-5b9b5c7ee8e3)


mv Command

The mv command is used to move a file or a directory form one location to another location.

## Syntax:

mv [source] [destination]

![image](https://github.com/user-attachments/assets/85ad95bb-84b7-48c0-9854-8af873af3a09)

![image](https://github.com/user-attachments/assets/ab5527bf-44ed-4d90-aea5-ea53c23f4277)

touch Command

Create empty file.

## Syntax:

touch [filename]

 ![image](https://github.com/user-attachments/assets/1cb614b5-956f-4733-831b-104c17f039dd)

vi Command

Edit file contents using editor.

## Syntax:
vi [filename]

![image](https://github.com/user-attachments/assets/16b5ee96-653c-4f28-924f-20514ea9b8fb)


## Result:

Thus, various Linux commands were executed successfully in Kali Linux virtual machine.
