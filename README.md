<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>        <img src="https://www.eniac.com/wp-content/uploads/2024/08/MicrosoftAzure.png"/>

</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used</h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>
- Prepare Domain Controller with Windows Server 2022 OS and a Windows 10 Client.
- Install Active Directory and Promote to Domain Controller  
- Create Domain Admin User and Organizational Units (OUs)  
- Join Client-1 to the Domain  
- Create Additional Users and Verify Access  

<h2>Deployment and Configuration Steps</h2>

### Part 1: Prepare Environment
NOTE: Always make sure that a public ip is assigned upon deployment of VM environments on the cloud. By making sure that they are in the same virtual network and subnet, both machines will talk to each other.

https://github.com/user-attachments/assets/c0d4a0a3-6d0a-42f5-8c2e-258341f1e03f



### Part 2: Install Active Directory








https://github.com/user-attachments/assets/fce7e66f-7493-4af1-bcd9-6b249349d008









---

### Part 3: Create a Domain Admin User and Organizational Units (OUs)






https://github.com/user-attachments/assets/da2bcfd7-d153-4fdb-8189-b6426c07309d







  

---

### Part 4: Join Client-1 to the Domain



https://github.com/user-attachments/assets/f23ad40a-f43c-429c-85cb-cc8ca2e57c9a



---

### Part 5: Create Additional Users and Verify Access



https://github.com/user-attachments/assets/291f2909-60ee-4c66-b6a6-e27a2024f273




---

### Conclusion

In this project, we successfully deployed and configured an on-premises Active Directory environment within Azure. By following these steps, we were able to install Active Directory, promote it to a Domain Controller, create Domain Admin users, organize the environment with Organizational Units (OUs), and join clients to the domain. The process ensures that Active Directory is fully functional in an Azure environment, enabling secure user management and network resources.
