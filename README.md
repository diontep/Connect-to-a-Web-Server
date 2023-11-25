<h1>Connect to a Web Server</h1>

<h2>Description</h2>
In this lab we're going to observe how packets are sent across the Internet using IP addresses.
<br />


<h2>Environments Used </h2>

- <b>Packet Tracer</b> 

<h2>Walkthrough:</h2>

<p align="center">
Part 1: Verify connectivity to the web server <br/>
<img src="https://i.imgur.com/02Z35ub.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Open the source host command prompt window. Select PC0.  <br/>
<img src="https://i.imgur.com/tmMmz4m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the Desktop Tab > Command Prompt. <br/>
<img src="https://i.imgur.com/8k93jbT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">
Verify connectivity to the web server. At the command prompt, ping the IP address of the web server by entering ping 172.33.100.50.

PC> ping 172.33.100.50

 

Pinging 172.33.100.50 with 32 bytes of data:

 

Reply from 172.33.100.50: bytes=32 time=0ms TTL=127

Reply from 172.33.100.50: bytes=32 time=0ms TTL=127

Reply from 172.33.100.50: bytes=32 time=0ms TTL=127

Reply from 172.33.100.50: bytes=32 time=0ms TTL=127

 

Ping statistics for 172.33.100.50:

Packets: Sent = 4, Received = 3, Lost = 1 (25% loss),

Approximate round trip times in milli-seconds:

Minimum = 0ms, Maximum = 0ms, Average = 0ms
<p align="center">
A reply verifies connectivity from the client to the destination web server. The reply may time out initially while devices load and ARP is performed.  <br/>
<img src="https://i.imgur.com/Kad1CSV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">
Close the command prompt window only, by selecting the x within the command prompt window. Be sure to leave the PC0 configuration window open  <br/>
<img src="https://i.imgur.com/PHLnwud.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Part 2: Connect to the Web Server via the web client <br/>
<img src="https://i.imgur.com/Kjg1hPL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">  
In the Desktop tab on PC0, select Web Browser.  <br/>
<img src="https://i.imgur.com/rl1NbZI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p align="center">
Enter 172.33.100.50 into the URL and click Go. The web client will connect to the web server via the IP address, and open the web page.
What messages did you see after the web page has finished loading?
<img src="https://i.imgur.com/heSDsIo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
