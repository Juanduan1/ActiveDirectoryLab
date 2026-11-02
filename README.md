<h1>Active Directory Lab</h1>


<h2>Description</h2>
I built an enterprise network from scratch using Oracle VirtualBox, Windows Server 2019, and a Windows 10 workstation. I configured the server as a Domain Controller running Active Directory, set up a dedicated internal subnet with DHCP and NAT routing, and configured DNS forwarders so internal machines could access the internet safely. To test directory scaling, I wrote a PowerShell script to automate the provisioning of over 1,000 user accounts into specific OUs, which gave me hands-on experience troubleshooting identity management and network handshakes.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Machine</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Project Walk-Through:</h2>

<p align="center">
Mock 1000 users: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
  
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
