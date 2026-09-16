# ActiveDirectoryLabs
<h1>Adding a Windows 11 Pc to my domain</h1>


<h2>Description</h2>
This project consists of configuring a Windows workstation to connect to an Active Directory environment and join it to a newly established domain. I configured the network settings, verified DNS connectivity to the Domain Controller, and added the workstation to the domain using authorized administrative credentials. The successful domain join was then verified to ensure the workstation could communicate with and authenticate through the Active Directory environment.
<br />


<h2>Languages and Utilities Used</h2>

- <b>VMware Workstation</b> 


<h2>Environments Used </h2>

- <b>Windows 11</b> 
- <b>Windows server</b> 
<h2>ActiveDirectory walk-through:</h2>

<p align="center">
In Users and Computers of AD create a new Organizational unit named Administratives: <br/>
<img src="https://i.imgur.com/uYLepef.png"/>
<br />
<br />
Create a new user in said PDU, then right-click and select "add to a group":  <br/>
<img src="https://i.imgur.com/nbaKIST.png"/>
<br />
<br />
in the empty space type in "Domain Admins" and click ok: <br/>
<img src="https://i.imgur.com/JuN3kYW.png"/>
<br />
<br />
to check if User was successfuly added select properties->member of:  <br/>
<img src="https://i.imgur.com/gxe0cQA.png"/>
