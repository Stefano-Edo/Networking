<h1>Networking</h1>

<h2>Description</h2>
Creating a workplace network environment using VM's. 
<br />


<h2>VM Platform</h2>

- <b>VirtualBox</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Walk-through:</h2>

<p align="center">
Configure IP Adressing for office internal network: <br/>
<img src="https://imgur.com/7XZudeM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Right click internal network navigate to properties:  <br/>
<img src="https://imgur.com/PsrdiRw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Double click on IPV4 to access its configuration: <br/>
<img src="https://imgur.com/WaPU3fG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Fill in IP Adress, Subnet mask, and DNS based on workplace requirements:  <br/>
<img src="https://imgur.com/5MYRe5Z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install remote adressing to configure NAT that allows our clients access to the internet through our private IP address:  <br/>
<img src="https://imgur.com/1GhNEZu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After setting up remote addressing install NAT:  <br/>
<img src="https://imgur.com/Xk4woKV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Green arrow pinting up indicates NAT has been installed:  <br/>
<img src="https://imgur.com/iyzd1Xc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install DHCP to give clients public IP addresses to browse the internet:  <br/>
<img src="https://imgur.com/DVgJbjy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set scope for DHCP, the range of IP addresses your clients can recieve:  <br/>
<img src="https://imgur.com/PHrGNLI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set Scope...: <br/>
<img src="https://imgur.com/RPxwLZZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Complete DHCP configuration: <br/>
<img src="https://imgur.com/FQahXFh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
With our client we ping Goolge and our domain to see if our networking works, we recieve replies on both: <br/>
<img src="https://imgur.com/9nEPksy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
