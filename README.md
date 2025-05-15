Active Directory Lab (Azure + PowerShell)

This is a hands-on lab I built to simulate a real-world Windows Server environment using Azure VMs, Active Directory, and PowerShell. This project demonstrates my ability to configure domain infrastructure, manage users, set up organizational units, and connect client machines to a domain. These are essential skills for IT Support and System Administration roles.

Tools and Technologies

- Windows Server 2022 (Azure VM)
- Active Directory Domain Services (AD DS)
- PowerShell
- DNS Configuration
- Azure Networking

Lab Summary

- Created two Azure VMs: Domain Controller and Client Machine
- Configured the testhub.local domain on the domain controller
- Installed Active Directory and promoted the VM to a Domain Controller
- Used PowerShell to bulk-generate users and assign them to an OU called Staff
- Created a Security Group and added members
- Created an Admin OU and assigned a user to the Domain Admins group
- Configured the client VM’s DNS to the domain controller’s IP (10.0.0.4) to join the domain
- Verified that the client machine appeared in Active Directory Users and Computers

Screenshots

VM Setup in Azure

![Screenshot 2025-05-15 at 3 20 22 AM](https://github.com/user-attachments/assets/7ce16cf2-b601-4743-b763-209471f8b1dd)

![Screenshot 2025-05-15 at 3 21 00 AM](https://github.com/user-attachments/assets/acc8c7a8-789b-49ac-a50a-012b74d89926)

Active Directory Installed

![Screenshot 2025-05-15 at 3 22 48 AM](https://github.com/user-attachments/assets/91e1b60b-97de-4ac5-bb25-1d93f4367656)


PowerShell User Creation

![Screenshot 2025-05-15 at 3 24 19 AM](https://github.com/user-attachments/assets/7b830edc-a318-4bfd-9865-63b80bd71654)


Staff OU and Admin OU

![Screenshot 2025-05-15 at 3 24 48 AM](https://github.com/user-attachments/assets/4056c1f8-da9d-4bb0-9aa9-0aee73f51abb)

DNS Config on Client

![Screenshot 2025-05-15 at 3 30 09 AM](https://github.com/user-attachments/assets/7e8b9b86-99bf-4c8c-b78d-42003f08a61f)

![Screenshot 2025-05-15 at 3 29 13 AM](https://github.com/user-attachments/assets/da7cdcf1-25f3-432a-94f7-5db84f601849)

Client in Domain

![Screenshot 2025-05-15 at 3 31 03 AM](https://github.com/user-attachments/assets/2d537cd1-4502-4ea2-986b-c35528bdc496)

