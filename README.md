<h1> Basic Wireshark Lab </h1>

<h2>Description</h2>
In this lab, Wireshark was used to capture and analyze network traffic during an Nmap scan, applying various filters such as ICMP and specific IP addresses to isolate relevant packets. The assignment also explored basic Linux and Windows commands for directory navigation, file management, and network operations. Emphasis was placed on understanding the role of timestamps in packet analysis, identifying protocols and ports commonly associated with network traffic, and recognizing potential security threats through anomalies in network patterns. This lab provided hands-on experience with essential network diagnostic tools, highlighting their significance in cybersecurity monitoring and troubleshooting.
<br />

<h2>Languages and Utilities Used</h2>

- <b> Wireshark </b> 
- <b> Nmap </b>
- <b> Linux Termninal </b>

<h2>Environments Used </h2>

- <b> Kali Linux VM </b>

<h2>Project walk-through:</h2>
<p align="left">
Wireshark was used to capture and display network packets from the Nmap scan. <br/><br/>
  <img src="Screenshot 2025-05-01 125135.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The ICMP filter was applied in Wireshark to capture relevant network traffic. <br/><br/>
  <img src="Screenshot 2025-05-01 125142.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The specific IP address of the Windows VM was identified and displayed in the Wireshark  <br/> capture. <br/><br/>
  <img src="Screenshot 2025-05-01 125149.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The first additional filter was applied to capture traffic on Port 53, typically  <br/> associated with DNS communications. <br/><br/>
  <img src="Screenshot 2025-05-01 125157.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The second additional filter was applied to capture traffic specifically from the IP  <br/> address 192.168.1.101. <br/><br/>
  <img src="Screenshot 2025-05-01 125204.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
<p align="left">
The saved results from the Wireshark scan are displayed, capturing network traffic for  <br/> further analysis. <br/><br/>
  <img src="Screenshot 2025-05-01 125210.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <br/>
