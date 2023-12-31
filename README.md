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
- Using the domain controller, using the Server Manager, under "Computers and Users" on Active Directory create a Security Group on the domain.
<img width="1680" alt="Screen Shot 2023-10-11 at 10 51 27 PM" src="https://github.com/Marionjr/NetworkFileSharesPermissions/assets/130338872/5d17e29b-2777-4e9d-9b09-0f70756bac35">

Using the Domain Controller, under the C-Drive Directory, create three folders, "No-Access"


<img width="1680" alt="Screen Shot 2023-10-11 at 10 51 27 PM" src="https://github.com/Marionjr/NetworkFileSharesPermissions/assets/130338872/ff94e52e-1deb-4d97-b1dd-e1a54a4fd216">

Using the Domain Controller, under the C-Drive Directory, create three folders, "Read-Access"


<img width="1680" alt="Screen Shot 2023-10-11 at 10 52 17 PM" src="https://github.com/Marionjr/NetworkFileSharesPermissions/assets/130338872/11d1f030-4855-4916-9d2f-15769453533f">

Using the Domain Controller, under the C-Drive Directory, create three folders, "Write-Access"
