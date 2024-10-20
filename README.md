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

- Log into a VM with Remote Desktop and download the osTicket installation files
- Install and enable Internet Information Services (IIS)
- Install MySQL and setup username and password
- Configure permissions and install osTicket

<h2>Installation Steps</h2>


<p>
<img src="https://i.imgur.com/isguyko.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
First, I created a virtual machine on Azure and logged into it. Then I downloaded the osTicket installation files and unzipped them. Then extracted them all. 
</p>
<br />

<p>
<img src="https://i.imgur.com/izbfKvf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, I have to enable Internet Information Services. So I opened control panel and on the left I clicked on "Turn Windows features on or off". Then I scrolled down to IIS and checked the box to enable it. 
</p>
<br />

<p>
<img src="https://i.imgur.com/sBhV46D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now within the osTicket installation folder, I installed PHP Manager, Rewrite Module, VC_redist and MySQL.  
</p>
<br />

<p>
<img src="https://i.imgur.com/3FqBEYx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After installing MySQL, I went on and started configuring it. Created a username and password. 
</p>
<br />

<p>
<img src="https://i.imgur.com/sBhV46D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next I opened IIS as admin, registered PHP from within IIS, and then finally installed osTicket. 
</p>
<br />

<p>
<img src="https://i.imgur.com/sBhV46D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/sBhV46D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/sBhV46D.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

