<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install CGI - Install PHP Manager for IIS
- Install Rewrite Module 
- Create Directory C:\PHP - Download PHP
- Install Redist & MYSQL

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/9JZPjAU.png" height="80%" width="80%" alt="RG&VM"/>
</p>
<p>
Using Azure, I first created a resource group and a virtual machine running on Windows 10. I then remote desktop connected to VM1 and started the installation process of OsTicket.
</p>
<br />


<p>
<img src="https://i.imgur.com/IJKjVVg.png" height="80%" width="80%" alt="CGI"/>
</p>
<p>
<img src="https://i.imgur.com/YEJgzPe.png" height="80%" width="80%" alt="IIS Download"/>
</p>
<p>
<img src="https://i.imgur.com/ABchKWM.png" height="80%" width="80%" alt="ReWrite Module"/>
</p>
Next I turned on CGI and enabled Internet Information Services (IIS). CGI is needed to install IIS. I then installed IIS, which is a webserver that allows the computer to serve up websites. Rewrite Module's installation followed next, which is just a requirement needed for OSticket to properly function. 
</p>
<br />

<p>
<img src="https://i.imgur.com/LN8VY90.png" height="80%" width="80%" alt="PHPs"/>
</p>
<p>
<img src="https://i.imgur.com/Lt7IguJ.png" height="80%" width="80%" alt="MQSYL"/>
</p>
First I created a directory for PHP in C Drive and then I installed PHP and extracted the files into the folder. After that, I installed MSQL. Next I opened IIS as an Admin to register PHP.
<p>
<img src="https://i.imgur.com/GskYkSa.png" height="80%" width="80%" alt="RGSTRPHP"/>
</p>
I registered the PHP in the folder created earlier and once complete, restarted IIS. Next I downloaded OSticket from the installation files and  
