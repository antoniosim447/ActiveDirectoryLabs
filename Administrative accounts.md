# ActiveDirectoryLabs
<h1>Creating and configuring Admistrative accounts</h1>


<h2>Description</h2>
Project consists of creating and configuring an administrative account in Active Directory with the appropriate permissions for managing users, computers, and domain resources.
<br />


<h2>Languages and Utilities Used</h2>

- <b>VMware Workstation</b> 


<h2>Environments Used </h2>

- <b>Windows 10</b> 
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
