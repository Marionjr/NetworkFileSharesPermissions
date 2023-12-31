# NetworkFileSharesPermissions
How to Share files through the network and managing permissions


<p align="center">
<img width="1680" alt="Screenshot 2023-12-30 at 10 19 01 PM" src="https://github.com/Marionjr/NetworkFileSharesPermissions/assets/130338872/36960176-ddff-4c6c-a2f6-0aeb61d4e45b">

</p>

<h1>Network File Sharing and Permissions </h1>
In this tutorial, we will share out resources on the network, give permissions and deny access to individual domain users and groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Server Manager
- Active Directory
  

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Windows Server 2019

<h2>High-Level Steps</h2>

- Using the Domain Controller, under the C-Drive Directory, create three folders, "No-Access," "Read-Access," and "Write-Access"
- Using Client-1 as a host on the domain, login as a domain user and reach the network path of network shared resources "//dc-1"
- As a user of the domain, attempt to read "No-Access" and observe the denial of access prompt.
- As a user of the domain, attempt to read "Read-Access" and attempt to create or modify a file. Observe the denial of access prompt.
- As a user of the domain, attempt to read "write-Access" and attempt to create or modify a file.
- Using the domain controller, using the Server Manager, under "Computers and Users" on Active Directory create a Security Group "Accountants" on the domain.
- Add a user to the "accountants" Security Group and make them a member with Read/Write permissions through Active Directory.
- Restart the host computer on the domain and sign in as the added user of the "accountants" security groups.
- Using the Domain Controller, under the C-Drive Directory, create "Accountants" and share the folder into the domain with read and write permissions.
- As a user of the "Accountants" Security Group, attempt to read and modify the shared "accountants" folder.

 <img width="1680" alt="Screen Shot 2023-10-11 at 10 51 27 PM" src="https://github.com/Marionjr/NetworkFileSharesPermissions/assets/130338872/5d17e29b-2777-4e9d-9b09-0f70756bac35">

Using the Domain Controller, under the C-Drive Directory, create three folders, "No-Access"


<img width="1680" alt="Screen Shot 2023-10-11 at 10 51 27 PM" src="https://github.com/Marionjr/NetworkFileSharesPermissions/assets/130338872/ff94e52e-1deb-4d97-b1dd-e1a54a4fd216">

Using the Domain Controller, under the C-Drive Directory, create three folders, "Read-Access"


<img width="1680" alt="Screen Shot 2023-10-11 at 10 52 17 PM" src="https://github.com/Marionjr/NetworkFileSharesPermissions/assets/130338872/11d1f030-4855-4916-9d2f-15769453533f">

Using the Domain Controller, under the C-Drive Directory, create three folders, "Write-Access"


<img width="1680" alt="Screen Shot 2023-10-11 at 10 56 25 PM" src="https://github.com/Marionjr/NetworkFileSharesPermissions/assets/130338872/b2ece609-d23e-4d2d-9cce-17564871d9bd">

As a user of the domain, attempt to read "No-Access" and observe the denial of access prompt.

<img width="1680" alt="Screen Shot 2023-10-11 at 10 56 47 PM" src="https://github.com/Marionjr/NetworkFileSharesPermissions/assets/130338872/0256819e-ba87-4f22-8d16-3a6b6ffd3a48">

As a user of the domain, attempt to read "Read-Access" and attempt to create or modify a file. Observe the denial of access prompt.


<img width="1680" alt="Screen Shot 2023-10-11 at 10 57 18 PM" src="https://github.com/Marionjr/NetworkFileSharesPermissions/assets/130338872/ae591e99-d985-4c01-b9bf-820fea36b106">

As a user of the domain, attempt to read "write-Access" and attempt to create or modify a file.


<img width="1680" alt="Screen Shot 2023-10-11 at 10 58 20 PM" src="https://github.com/Marionjr/NetworkFileSharesPermissions/assets/130338872/812321a7-6d18-49c2-bb17-4f0c1bbec029">


Using the domain controller, using the Server Manager, under "Computers and Users" on Active Directory create a Security Group "Accountants" on the domain.


<img width="1680" alt="Screen Shot 2023-10-11 at 10 58 20 PM" src="https://github.com/Marionjr/NetworkFileSharesPermissions/assets/130338872/e9d7e021-d41d-4428-8e67-0cf37a339b46">


Using the domain controller, using the Server Manager, under "Computers and Users" on Active Directory create a Security Group "Accountants" on the domain.


<img width="1680" alt="Screen Shot 2023-10-11 at 10 58 43 PM" src="https://github.com/Marionjr/NetworkFileSharesPermissions/assets/130338872/30c34d00-8709-4dd6-86f7-41c0da32c026">

Add a user to the "accountants" Security Group and make them a member with Read/Write permissions through Active Directory.

<img width="1680" alt="Screen Shot 2023-10-11 at 10 59 39 PM" src="https://github.com/Marionjr/NetworkFileSharesPermissions/assets/130338872/bfd0dce7-af18-424a-ac2a-ac7c4d575f1b">

Using the Domain Controller, under the C-Drive Directory, create "Accountants" and share the folder into the domain with read and write permissions.


<img width="1680" alt="Screen Shot 2023-10-11 at 11 02 17 PM" src="https://github.com/Marionjr/NetworkFileSharesPermissions/assets/130338872/0abb6128-3e99-49da-91b2-c824ad6ce196">

As a user of the "Accountants" Security Group, attempt to read and modify the shared "accountants" folder.
