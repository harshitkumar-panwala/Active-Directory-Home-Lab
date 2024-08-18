# Active Directory Implementation in Windows Server 2019
This project is a comprehensive guide for setting up and managing an Active Directory (AD) environment using Windows Server 2019 and a Windows 10 client in Oracle VirtualBox.

# Documentation
[Active Directory Project Documentation](https://github.com/harshitkumar-panwala/Active-Directory-Home-Lab/blob/main/Active%20Directory%20Project%20Documentation.pdf) provides detailed instructions on setting up an AD environment, including configuring DNS, DHCP, and integrating a client machine into the domain. This document will guide you through the entire process step-by-step.

# Network Diagram
[Network_Diagram.pdf](https://github.com/harshitkumar-panwala/Active-Directory-Home-Lab/blob/main/Network_Diagram.pdf) can be accessed here. This diagram visually represents the network setup, including the Domain Controller, Windows 10 client, and the internal/external network configurations.

# PowerShell Script
[User_Creation.ps1](https://github.com/harshitkumar-panwala/Active-Directory-Home-Lab/blob/main/User_Creation.ps1) is the PowerShell script used to automatically generate 100 user accounts within the Active Directory. Be sure to update the script with your own user list file and adjust any settings as needed for your environment.

# User List
The file [names.txt](https://github.com/harshitkumar-panwala/Active-Directory-Home-Lab/blob/main/names.txt) contains the list of 100 users that need to be created in the Active Directory. This file is referenced by the PowerShell script during the user creation process. Each user account is generated based on the entries in this file.
