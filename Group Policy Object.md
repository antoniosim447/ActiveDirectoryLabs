# ActiveDirectoryLabs
<h1>Managing Group Policy Object</h1>


<h2>Description</h2>
Project consists of creating and managing Group Policy Objects (GPOs) within Active Directory to centrally control user and computer settings. I configured policies such as password requirements, account lockout settings, and security restrictions, then applied and tested the GPOs on domain-joined computers to verify they were working correctly.
<br />


<h2>Languages and Utilities Used</h2>

- <b>VMware Workstation</b> 


<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b>Windows server</b> 
<h2>ActiveDirectory walk-through:</h2>

<p align="center">
In server dashboard click manage then Add Roles and Features: <br/>
<img src="https://i.imgur.com/NVMnhRc.png"/>
<br />
<br />
Click next->Role-based installation->next->select your server :  <br/>
<img src="https://i.imgur.com/7dj58rQ.png"/>
<br />
<br />
Next->Select Active Directory Domain Services: <br/>
<img src="https://i.imgur.com/C6nyeEz.png"/>
<br />
<br />
Click next until you reach confirmation screen and choose to install:  <br/>
<img src="https://i.imgur.com/9g0GEz7.png"/>
<br />
<br />
After installing click on flag and select the option to promote server to a Domain Controller:  <br/>
<img src="https://i.imgur.com/zB7gzLC.png"/>
<br />
<br />
Add a new forest and name your domain:  <br/>
<img src="https://i.imgur.com/LG7g2aR.png"/>
<br />
<br />
Follow steps untill you arrive at installation screen and select install:  <br/>
<img src="https://i.imgur.com/yaB9MF5.png"/>
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
