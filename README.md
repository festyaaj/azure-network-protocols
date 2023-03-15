<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Use Powershell and Wireshark
- Use SSH to log into Linux Virtual Machine
- Monitor DNS traffic

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/J9lD7UM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Pinged another Virtual Machine in Powershell to see ICMP traffic in Wireshark
</p>
<br />

<p>
<img src="https://i.imgur.com/MQGG7wz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Used SSH on Powershell to log into Linux virtual machine. Filtered Wireshark to show SSH traffic.
</p>
<br />

<p>
<img src="https://i.imgur.com/E5o3Hnj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Used nslookup on Powershell to monitor DNS traffic from www.google.com on Wireshark
</p>
<br />
