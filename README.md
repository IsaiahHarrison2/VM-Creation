<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>How to Create a Virtual Machine(Azure)</h1>
This tutorial outlines how to create a Virtual Machine within Azure Virtual Machines.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services


<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Log into portal.azure.com
- Create a Resource Group
- Create a Virtual Machine
- Use Microsoft Remote Desktop

<h2>Deployment and Configuration Steps</h2>

<p>
<img width="1632" alt="72DE23BE-0D0E-4314-93BF-7A31DC2AF8AD" src="https://github.com/user-attachments/assets/7abc61c8-5fad-406e-8ab6-1aa68f10581d" />
</p>
<p>
First, you want to login into portal.azure.com an locate/and or search for the resource group. Press Create, make a resource group name. Make sure when doing this you put everything in the same region. (West US 2) Press review + create and create.
</p
<br />

<p>
<img width="1632" alt="A25FE2C8-2BAF-4B63-A3AA-F8882D475520" src="https://github.com/user-attachments/assets/19a29e86-6922-4e5e-8b82-8fa09cbd29ba" />
<p>
Once you have completed the process of creating a resource Group, you should then proceed towards creating a Virtual Machine. (search or locate Virtual Machines tab) While using VM, find your resource group name, then create a VM name, "MAKE SURE REGIONS ARE THE SAME', pick an image (Windows Server, Windows 10, Ubuntu, Red Hat) Create a Username and Password for your VM. Go through an make sure everything else is good as far as networking, disk or tags or looking good and then create.
</p>
<br />

<p>
<img width="1173" alt="00A50CE6-555E-4E00-B094-7A8D1482ECE1" src="https://github.com/user-attachments/assets/5e059e5c-8392-4d34-b979-b66f71129ae2" />

</p>
<p>
Lastly, Go back to your VM tab and find the Public IP address and copy it into your Microsoft Remote Desktop app (for Mac users) or Remote Desktop to connect to the Virtual Machine. If using Microsoft Remote Desktop, find the ( + ) sign in the top right hand corner. Add the IP address to PC and youll be up an running.
<br />
