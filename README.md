<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
I observed various network traffic to and from Azure Virtual Machines with Wireshark as well as experimented with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- observe Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

-  Install Wireshark
- open command prompt
- I installed Wireshark to enhance network troubleshooting and analysis capabilities. Wireshark is a powerful tool that allows for the capture and detailed inspection of network traffic in real-time. By installing this application, I was able to monitor, diagnose, and resolve network-related issues more efficiently. Wireshark's comprehensive analysis features enabled me to identify bottlenecks, detect suspicious activity, and ensure the smooth operation of network services. This installation was essential for maintaining robust network performance and security, making it a critical component of my IT toolkit.
- cleanup 

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I installed Wireshark to enhance network troubleshooting and analysis capabilities. Wireshark is a powerful tool that allows for the capture and detailed inspection of network traffic in real-time. By installing this application, I was able to monitor, diagnose, and resolve network-related issues more efficiently. Wireshark's comprehensive analysis features enabled me to identify bottlenecks, detect suspicious activity, and ensure the smooth operation of network services. This installation was essential for maintaining robust network performance and security, making it a critical component of my IT toolkit.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
This is where i open the command prompt to start playing aroung with my system communication the diffrent servers like DNS and protocols such as SSH.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Using Wireshark, I observed various network protocols including SSH, RDP, DNS, HTTP/S, and ICMP. Wireshark's comprehensive packet analysis capabilities allowed me to inspect the traffic for each protocol in real-time or by analyzing captured data. By monitoring SSH sessions, I ensured secure remote access to systems. With RDP, I verified smooth remote desktop connections. DNS traffic analysis helped in resolving domain names and detecting any DNS-related issues. HTTP/S inspection allowed me to analyze web traffic for troubleshooting website performance or security concerns. ICMP packet analysis assisted in monitoring network connectivity and diagnosing potential network issues. Overall, leveraging Wireshark to observe these diverse network protocols provided valuable insights into network behavior, aiding in troubleshooting and ensuring optimal network performance and security.
</p>
<br />
