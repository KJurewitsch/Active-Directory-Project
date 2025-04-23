# Active-Directory-Project
Actived Directory Project I did in march 2025, will do another one soon.
<h1>Windows server 2019 Virtual active directory project</h1>

<h2>Description</h2>
This Project was done as a class project to learn the understandings on how to create an active directory on a Virtual Machine, creating a Domain Controller and a DHCP server
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtualbox Virtual Machine</b>
- <b>Windows Server Manager</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Windows Server 2019 ISO</b>

<h2>Concepts </h2>

- <b>DHCP</b>
- <b> Domain Controller</b>
- <b> IP Address</b>

<h2> Walk-through:</h2>

<p align="center">
We make my server active directory first after setting up the Virtual PC. : <br/>
<img src="https://i.imgur.com/vXsPqXz.png" height="80%" width="80%" alt="Active Domain Steps"/>
<br />
<br />
The DHCP Server is set up. That way we have a default gateway:  <br/>
<img src="https://i.imgur.com/09UpdNH.png" height="80%" width="80%" alt="Active Domain Steps"/>
<br />
<br />
Server networks are both up: <br/>
<img src="https://i.imgur.com/Kob9xp7.png" height="80%" width="80%" alt="Active Domain Steps"/>
<br />
<br />
Here we can see that both DHCP and IPv4 are up along side Remote Access:  <br/>
<img src="https://i.imgur.com/DxBnFPv.png" height="80%" width="80%" alt="Active Domain Steps"/>
<br />
<br />
If we go back in time we can see it took a while for everything to get running. Here is Remote Access getting installed:  <br/>
<img src="https://i.imgur.com/CTPKWmE.png" height="80%" width="80%" alt="Active Domain Steps"/>
<br />
<br />
We Used Powershell to add a bunch of users into the directory:  <br/>
<img src="https://i.imgur.com/ZSym1mR.png" height="80%" width="80%" alt="Active Domain Steps"/>
<br />
<br />
The script is finished and all the users are added:  <br/>
<img src="https://i.imgur.com/6IgiEyu.png" height="80%" width="80%" alt="Active Domain Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
