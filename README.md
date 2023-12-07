
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Azure tenant 
- Active Azure subscription

<h2>Installation Steps</h2>

<h3>1. Create the resources in Azure</h3>
<p>
- Open your browser and go to portal.azure.com <br>
- Click Resource groups <br>
- Click Create resource group <br>
- Give your resource group a name <br>
- Set your Region <br>
- Click Review + create <br>
- Click Create <br>
- Search Virtual machines <br>
- Click Create, then Azure virtual machine <br>
- For Resource group select the resource group you previously created <br>
- Give the virtual machine a name <br>
- Set the Region <br>
- Set the Image to Windows 10 Pro <br>
- Set the Size to 2 or 4 vcpu <br>
- Use a username and password that you will not forget <br>
- Confirm and tick the licensing checkbox <br>
- Select Review + create 
- Select Create
</p>
<br/>

<p>
<h3>Installation</h3>
</p>
<p>
 - Go to portal.azure.com <br>
 - Click Virtual machines <br>
 - Copy the public IP address of the virtual machine you created <br>
 - Click Start <br>
 - Search Remote desktop connection <br> 
 - Enter the public IP address of the virtual machine you created, then press Connect <br>
 - Click More choices <br>
 - Click Use a different account <br>
 - Enter the username and password you created for the virtual machine <br> <br>

<p> <strong>Install/ enable IIS</strong> <br>
- Right click Start <br>
- Click Run <br>
- Type control panel, press OK <br>
- Click Programs <br>
- Click Turn Windows features on or off <br>
- Tick the checkbox for Internet Information Services and expand it <br>
- Expand World Wide Web Services <br>
- Expand Application Development Features <br>
- Check CGI <br>
- Collapse Application Development Features <br>
- Expand Common HTTP Features <br>
- Tick all checkboxes inside of Common HTTP Features <br>
- Click OK <br>
- To test that the web server is running, go to a web browser and enter 127.0.0.1 <br> <br>
</p>

<p><strong>Download and install PHP Manager for IIS:</strong> <br>
  - Download PHP Manager for IIS at https://drive.google.com/file/d/1RHsNd4eWIOwaNpj3JW4vzzmzNUH86wY_/view <br> <br>
</p>

<p><strong>Download and install the Rewrite Module:</strong> <br>
  - Go to the link https://drive.google.com/file/d/1tIK9GZBKj1JyUP87eewxgdNqn9pZmVmY/view <br>
</p>

<p><strong>Create the directory C:\PHP</strong> <br>
 - Go to File Explorer <br>
 - Go to C: <br>
 - Right click, New, Folder, name the folder PHP <br>
</p>
  
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
