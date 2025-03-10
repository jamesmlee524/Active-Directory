<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Create Domain controller on Azure
- Setup Client 1 in Azure
- Set Domain Controller’s NIC Private IP address to be static
- Ping DC-1's private IP address to ensure connection

<h2>Deployment and Configuration Steps</h2>

Overview of setup and deployment process:
<img width="1536" alt="Screenshot 2025-03-10 at 3 53 55 PM" src="https://github.com/user-attachments/assets/db8006f0-55a4-404b-999b-bc5f530649b9" />

<br/>
<br/>
Create Domain controller on Azure
<p>
<img width="1536" alt="Screenshot 2025-03-10 at 3 57 04 PM" src="https://github.com/user-attachments/assets/bc3c79b3-47eb-4615-9b69-cc74c4ff14da" />

</p>

<br />
Setup Client 1 in Azure
<p>
<img width="1536" alt="Screenshot 2025-03-10 at 3 58 20 PM" src="https://github.com/user-attachments/assets/34c7cb2e-e3f5-4bb9-8b43-78323ac24ffc" />

</p>
<br />
Set Domain Controller’s NIC Private IP address to be static
<p>
<img width="1536" alt="Screenshot 2025-03-10 at 3 59 08 PM" src="https://github.com/user-attachments/assets/dc1a574c-1f22-4486-89c1-1ff8529f7a11" />

</p>
<br />

Ping DC-1's private IP address to ensure connection
<img width="1536" alt="Screenshot 2025-03-10 at 4 01 42 PM" src="https://github.com/user-attachments/assets/0e26080f-4a87-43e0-a787-6fcfe881f6a9" />


