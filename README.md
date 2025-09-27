<h1>Azure Lab</h1>


<h2>Description</h2>
Hands-on labs from my Azure Fundementals training. Includes screenshots, steps, and lessons learned.
<br />


<h2>Utilities Used</h2>

- <b>Microsoft Azure</b>
- <b>Microsoft Powershell</b>
- <b>Virtual Machines</b>
- <b>Remote Desktop Connection</b>
- <b>WireShark (Protocol Analyzer)</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (22H2)

<h2>Program walk-through: Creating resource groups & storage accounts</h2>

<p align="center">
Creating resource group: 1/2 <br/>
<img src=https://i.imgur.com/geciewC.png
<br />
<br />
2/2  <br/>
<img src=https://i.imgur.com/EvGU7Cz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating a storage account. *Only adjusting the "basics" tab, leaving everything else on default option: <br/>
<img src=https://i.imgur.com/3J2oSgy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Deployment completed:  <br/>
<img src="https://i.imgur.com/Oo4aNja.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Uploading trial text to storage account:  <br/>
<img src="https://i.imgur.com/ZMVyBQF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Editing text from within storage account /change in text now reflects in the note:  <br/>
<img src="https://i.imgur.com/bmw1cbx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Complete overview of storage account:  <br/>
<img src="https://i.imgur.com/ZhgAL37.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<h2>Program walk-through: Creating virtual machines for Windows & Ubuntu (Linux) and Conducting ICMP traffic examination</h2>

<p align="center">
Windows VM: <br/>
<img src="https://i.imgur.com/kXfVOKZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating Ubuntu (Linux) VM:  <br/>
<img src="https://i.imgur.com/a4hQJ7X.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Successful deployment of Ubuntu VM: <br/>
<img src="https://i.imgur.com/odyL73Y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirming that both VMs can successfully be located on the same network:  <br/>
<img src="https://i.imgur.com/d7PqW7i.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using remote desktop connection to connect to the Windows VM:  <br/>
<img src="https://i.imgur.com/S4zc5NL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Connection successful: <br/>
<img src="https://i.imgur.com/nl7OxMS.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installing software (Wireshark) within the Windows VM. Allowing myself to monitor traffic coming to and from VMs: <br/>
<img src="https://i.imgur.com/XkzqHaV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Inspecting data traffic (packets) on the backend of the network: <br/>
<img src="https://i.imgur.com/NlHMqQD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
A filtered search for ICMP traffic only. *As displayed, no results at the time: <br/>
<img src="https://i.imgur.com/x02Y5mH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using Microsoft Powershell to ping the Ubuntu VM using IPv4 address: <br/>
<img src="https://i.imgur.com/G6KYBHx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Data I received back from the PING command: <br/>
<img src="https://i.imgur.com/CXxVrny.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
 
<h2>Configuring a firewall within the network security group: </h2>

<p align="center">
Initiating a non-stop PING from the Windows VM: <br/>
<img src="https://i.imgur.com/7B20qxD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Disabling inbound traffic to Ubuntu VM from the Windows VM: <br/>
<img src="https://i.imgur.com/O9KLVSm.png"80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2/2: <br/>
<img src="https://i.imgur.com/D5FhsuO.png"80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Request timed out once incoming/inbound data was disabled and blocked by firewall: <br/>
<img src="https://i.imgur.com/8XYhUqO.png"80%" width="80%" alt="Disk Sanitization Steps"/>
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
