<p align="center">
<img src="https://github.com/user-attachments/assets/41fc2368-e629-4f94-a13f-c49857e10535" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Creating a Virtual Machine(Azure)</h1>
This tutorial outlines the creation of Resource Groups and Virtual Machines (VMs) for both Windows and Linux (Ubuntu), and operation of VMs.
We will also be creating a Virtual Network and Subnet.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)
- Linux (Ubuntu)

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/user-attachments/assets/24b53646-e606-47a4-9e64-6ec9b1d1ede0"
"
 height="80%" width="80%" alt="RG-Test Steps"/>
</p>
<p>
  Step 1: Login to your Azure Portal: portal.azure.com
  
  First, we need to create a Resource Group. A Resource Group is a logical container for organizing and managing related Azure resources as a single unit - essentially a folder that contain different types of Azure resources (virtual machines, databases, storage accounts. 
  Navigate to/Search for "Resources Groups"
  Click "Create" and name your Resource Group. Click "Review + Create" and "Create" to finish.

  Now that we have our Resource Group, we will create our Virtual Machine and Virtual Network with it.
  
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/42c051e6-dfd4-46e9-a7f7-076a3a9c619a" height="80%" width="80%" alt="VM"/>
</p>
<p>
Navigate to your home portal, and search for "Virtual Machines"
Click "Create" > "Azure Virtual Machine" > Select newly created Resource Group.
Navigate to "Image" - this is where you select the OS preferred for your Virtual Machine (DO NOT FORGET ABOUT THIS STEP).

  Select a size with at least two VCPUs.

Create Administrator Account. Make sure you have a way to remember your Username and Password!

Make sure to click "I confirm I have an eligible Windows 10/11 license with multi-tenant hosting rights." and then click "Review + Create"

Finish by clicking "Create" one last time. Now navigate back to your home portal, and select your resource group to preview the resources within it:
![image](https://github.com/user-attachments/assets/83a0a89c-7f5f-4fd6-89cb-3400c6b41245)
Repeat these steps and create a Linux (Ubuntu) VM on the SAME Resource Group and Virtual Network.

Next, we will confirm that we have two VMs. Navigate back to "Virtual Machines"
![image](https://github.com/user-attachments/assets/8d2e75a9-987f-4ddd-a351-488250dd6e43)

