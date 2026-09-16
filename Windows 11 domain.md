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
Configure the computer with an appropriate static IP address, subnet mask, and default gateway. The computer should use the Domain Controller's IP address as its preferred DNS server so it can locate the domain.: <br/>
<img src="https://i.imgur.com/41MCvVw.png"/>
<br />
<br />
Verify that the computer received the expected IP address, gateway, and DNS configuration. This confirms that the computer is properly connected to the network before attempting to join the domain.":  <br/>
<img src="https://i.imgur.com/969YlPy.png"/>
<br />
<br />
Open System Properties and select Change under the computer name and domain settings." and click ok: <br/>
<img src="https://i.imgur.com/mbYW7ET.png"/>
<br />
<br />
Select Domain and enter the name of the Active Directory domain, such as Antonioslab.com. Click OK to join the domain. Enter Admin credentials when asked then click ok:  <br/>
<img src="https://i.imgur.com/5DvKbLF.png"/>
<br />
<br />
The “Welcome to the [domain] domain” message confirms that the computer successfully joined the Active Directory domain. The computer ask you to restart then join as a domain user.:  <br/>
<img src="https://i.imgur.com/vW3yBly.jpeg"/>
