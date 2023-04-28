# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket. You will gain an understanding of how to install and use the osTicket system. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Setup a Virtual Machine in Azure
- Install the osticket requirements
- Install osTicket itself 
- Do the after-installation configuration of osTicket
- Explore osTicket as a Help Desk Professional ( create, interact, and close tickets )
- Clean up Virtual Environment in Azure

<h2>Installation Steps</h2>
 Click here for the resources for the installation: [Resources](https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6)
<p>
<img src="https://i.imgur.com/kMp0jCz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"First, go to https://portal.azure.com and create your first subscription. After logging in, navigate to 'Virtual Machines' and click on 'Create'."
</p>
<br />

<p>
<img src="https://i.imgur.com/CJ0aYxr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"Next, click on the first Virtual Machine option. Once you're in, you'll need to fill out the details for your VM (Virtual Machine)."
</p>
<br />

<p>
<img src="https://i.imgur.com/N7UycPF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"In the 'Details' section, leave the 'Resource group' field as is, as it will create one for you. Next, name your Virtual Machine whatever you'd like. After that, select a region of your choice, but keep in mind that the cost of the operating system you choose may differ from region to region. Next, select the 'Image' option and choose 'Windows 10 Pro'."
</p>
<p>
<img src="https://i.imgur.com/tJAusDE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"Next, in the 'Details' section, the 'Size' option determines the speed and cost of your Virtual Machine. If you want to see what all the operating systems have to offer, click on 'See all sizes'. Next, fill in your desired 'Username' and 'Password', which will be used to log in to your Virtual Machine. After that, click through until you reach the 'Network' section."
</p>
<p>
<img src="https://i.imgur.com/pT1FYAO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"Make sure you have a virtual network and a public IP address."
</p>
<p>
<img src="https://i.imgur.com/QrbujzC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"Once you click 'Create + review', it will take a moment to process. Once it's done, click 'Create'."
</p>
<p>
<img src="https://i.imgur.com/KIXGZxM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/k5Lxl1c.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</p>
<p>
"It will take a moment to process. Once it's done, click 'Go To Resources'."
</p>
<p>
<img src="https://i.imgur.com/mSjj0WR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"Click on the folder icon next to the Public IP address, and then pull up Remote Desktop on your Windows or Mac computer. (Note: To remotely connect to the VM on a Mac, you need to download Microsoft RDP first.)"
</p>
<p>
<img src="https://i.imgur.com/q9FFZxG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Gv6wUxC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"After you paste the Public IP address, you're going to click on 'Show Options'. Once you've clicked on 'Options', you will need to enter your username and then click 'Connect'.""
</p>
 <p>
<img src="https://i.imgur.com/oAqFSmA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
"Once you enter your password and you're on the home screen, follow these steps:

    Go to your Windows key and right-click the menu.
    Click on 'Run' and then type in 'Control Panel'.
    Click on 'Programs' and then select 'Turn Windows features on or off'.
    Click the box next to 'Internet Information Services' and then click the '+' sign."
</p>
<p>
<img src="https://i.imgur.com/LKVRfy5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 "Then, click on 'CGI' and then click 'Done'."
</p>
<p>
<img src="https://i.imgur.com/xv0UCWw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/3MEpKzg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 "Then, click on 'CGI' and then click 'stop Done'."
</p>
<p>
<img src="https://i.imgur.com/407QGem.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 "Then, click on 'CGI' and then click 'Done'."
</p>
<p>
<img src="https://i.imgur.com/LKVRfy5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 "Then, click on 'CGI' and then click 'Done'."
</p>
<br />
