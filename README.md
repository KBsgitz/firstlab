<h1>First Networking Lab - Basic LAN</h1>


<h2>Description</h2>
This project entails the subnetting process, design and configuration of a basic Local Area Network. 
<br />


<h2>Languages/Utilities Used</h2>

- <b>Cisco IOS</b> 

<h2>Environments Used </h2>

- <b>Packet Tracer</b>

<h2>Walk-through:</h2>

Starting range of 192.168.0.0/24 <br/>

3 different subnets are required:<br/>
•	Subnet A for servers/printers - 4 hosts consisting of 2 servers and 2 printers. <br/>
•	Subnet B for employees - 14 hosts consisting of 14 workstations. <br/> 
•	Subnet C for customers/guests - 72 hosts with Wi-Fi access. <br/>

<h2>SUBNETTING</h2>
VLSM (Variable Length Subnet Mask) will be applied, subnetting for requirements, avoiding wasting IP addresses. <br/>

1. Start with the largest subnet (C) for customers <br/>

192.168.0.0/24 is the beginning of the range. <br/>

First, the subnet mask needs to be converted to binary. The CIDR notation of '/24' represents 24 bits, meaning the subnet mask in binary is 11111111.11111111.11111111.00000000 <br/>

The 1's represent the network bits, with the 0's representing the host bits. I am going to use a table to 'save' bits from the host and convert the rest to the network, to allow for 72 hosts on subnet C. <br/>







<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
