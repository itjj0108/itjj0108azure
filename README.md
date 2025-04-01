<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used</h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 Sign in to Azure
- Step 2 Create a Virtual Machine
- Step 3 Configure Networking
- Step 4 Review & Create
- Step 5 Connect to Your VM
<h2>Deployment and Configuration Steps</h2>

<p>
<img src-<img width="1093" alt="Screenshot 2025-04-01 at 6 04 25 PM" src="https://github.com/user-attachments/assets/4adc2b17-5f95-442c-9521-a985a8059862" />
</p>
<p>
Step 1: Sign in to Azure
Go to Azure Portal.

Log in with your Microsoft account.</p>
<br />

<p>
<img src=<img 
</p>
<p>
 Step 2: Create a Virtual Machine
In the Azure Portal, search for "Virtual Machines" and click Create → Azure Virtual Machine.

Fill in the Basic details:

Subscription: Choose your Azure subscription.

Resource Group: Create a new one or use an existing one.

Virtual Machine Name: Enter a unique name.

Region: Select a data center near you.

Image: Choose an OS (Windows/Linux).

Size: Pick a VM size (Standard B1s for basic use).

Set Administrator Credentials (username & password).



Step 3: Configure Networking
Under Networking, use default settings or customize:

Virtual Network: Default or create new.

Subnet: Default or create new.

Public IP: Enable if you need external access.

</p>
<br />

<p>
<img src=
</p><img width="1093" alt="Screenshot 2025-04-01 at 6 21 18 PM" src="https://github.com/user-attachments/assets/4d728583-8d08-4f5c-810c-a229a24b7c9c" />
<p>
 Step 4: Review & Create
Click Review + Create.

Azure will validate your settings.

Click Create to deploy your VM.

Step 5: Connect to Your VM
Once deployed, go to Virtual Machines → select your VM.

Click Connect:

For Windows: Use RDP (Remote Desktop Protocol).

For Linux: Use SSH with a terminal.

</p>
<br />
