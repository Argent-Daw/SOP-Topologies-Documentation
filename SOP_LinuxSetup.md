# SOP: Linux System Setup

## Purpose:

This document is the procedure for setting up a Linux Computer

## Scope:

This SOP is to be used for creating a Linux System.

## Responsibilities:

The IT department is responsible for all implementation, maintenance and review of this policy.

## Prerequisites:

1. Obtain a computer
2. Obtain a USB with Ubuntu Client

## Procedure:

**Ubuntu USB Setup**
1. Obtain a USB stick with at least 4GB or higher
2. Obtain Rufus
3. Obtain a Ubuntu ISO file
4. Launch Rufus and insert the USB stick into Host computer
5. Select the Ubunto Iso File you previously downloaded
6. Write the ISO file, ensure that correct volume label is selected.
7. Write Warning and hit accept
8. Write ISO and hit accept
9. When Rufus is finished you should see a green ready bar at the bottom meaning the installation of the Ubuntu is completed.

**Ubuntu Desktop Installation**
1. Insert the USB Flash Drive into the Laptop ensure that the BIOS reflects the correct boot order.
2. Choose the appropriate language and go through the initial install options.
3. Make sure to choose a "Normal Installation"
4. When selection a type of installation choose the option: "Erase Disk and Install Ubuntu" we want a fresh installation
5. Create the administrator login credentials to be used for SUDO. Use the correct login and password according to the IT Department.
6. Complete the Installation and choose the Dark Mode option.
7. Remove USB after restart to complete process
8. Do not forget to Update the software using the software updater.

**Adding Ubuntu User Profile**
1. Open the terminal on your Linux system.
2. Execute the following command: sudo adduser username.
3. The command will prompt you to enter various details, such as password, full name, phone number, etc.
4. Fill in the required information as prompted.
5. The command will ask you if the information you entered is correct. Enter y or n then press enter to complete the user creation process.


## References:

* https://ubuntu.com/tutorials/create-a-usb-stick-on-windows#1-overview
* https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview

## Definitions:

* SOP - Standard Operating Procedure

## Revision History:

11/14/2023 - Created by Matthew Earles
