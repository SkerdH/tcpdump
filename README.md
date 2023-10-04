<h1>Analyzing Network Traffic with TCPDump</h1>


<h2>Description</h2>
Project consists of a few simple tcpdump commands, and an intro into wireshark. In this project I learned how to analyze network packets, and the different ways to display the data.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Tcpdump</b> 
- <b>Wireshark</b>
- <b>Windows Terminal</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Open Windows Terminal- using sudo to gain access test out different commands while limiting the packets to 10 using -c: 
<br/>
<img src="https://i.imgur.com/5z7sLFd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a script to utilize tcpdump. This command checks incoming, and outgoing packets on test website limiting it to 10:  
<br/>
<img src="https://i.imgur.com/H0WTnsP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creates a sequence of dump files placing it into captured.pcap. Maxed out at 1 million bites -C 1, and 15 seconds -G 15:  
<br />
<br />
<img src="https://i.imgur.com/XqxkQ12.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Captures all the tcp traffic for a Get- which is usually used for submitting a form:
<img src="https://i.imgur.com/qk4EadO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Use Wireshark to get better understanding of the meaning of each packet:  <br/>
<img src="https://i.imgur.com/0iikaDE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

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
