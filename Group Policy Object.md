# ActiveDirectoryLabs
<h1>Managing Group Policy Object</h1>


<h2>Description</h2>
Project consists of creating and managing Group Policy Objects (GPOs) within Active Directory to centrally control user and computer settings. I configured policies such as password requirements, account lockout settings, and security restrictions, then applied and tested the GPOs on domain-joined computers to verify they were working correctly. In this project I decided to disable all password policies to increase the speed at which I can create new accounts.
<br />


<h2>Languages and Utilities Used</h2>

- <b>VMware Workstation</b> 


<h2>Environments Used </h2>

- <b>Windows 10</b> 
- <b>Windows server</b> 
<h2>ActiveDirectory walk-through:</h2>

<p align="center">
In server dashboard click tools>Group Policy Management->Domain->Group policy object->Right-click on Default domain>Edit: <br/>
<img src="https://i.imgur.com/JsmhJH1.png"/>
<br />
<br />
Select Computer Configurations>Policies->Window Settings->Security settings->and select Account policies:  <br/>
<img src="https://i.imgur.com/rtUmWPj.png"/>
<br />
<br />
Next->Input the settings you want: <br/>
<img src="https://i.imgur.com/i3Gnrp3.png"/>
<br />
<br />
Now we are going to create a Group and add users to it, to add users click on the group->Member->add:  <br/>
<img src="https://i.imgur.com/nzEdLqH.png"/>
<br />
<br />
Go back to file explorer and create a file named Tech_users, in the security settings->advanced->disable inheritance->remove all groups excluding admins-> add Tech_users->then share the folder to create a route-> :  <br/>
<img src="https://i.imgur.com/3P2SByg.png"/>
<br />
<br />
Now enter GPO and under your domain find the folder with your group and right click to add a new GPO and name it Tech_drive->right click->edit->user config->prefrences->right click drive maps->new->mapped drive->under the action tab change it to create->input the folder route into location->common tab->check Item level targeting->tageting->New Item 'security group'->add Tech_users to group->apply :  <br/>
<img src="https://i.imgur.com/Kylrjml.png"/>
<br />
<br />
Congratulations you have now made a shared drive and folder for the group Tech_users:  <br/>
<img src="https://i.imgur.com/9Zu6Mis.png"/>
</p>
Add a new forest and name your domain:  <br/>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
