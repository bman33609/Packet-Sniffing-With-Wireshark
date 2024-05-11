<h1>Packet Sniffing With Wireshark</h1>


<h2>Description</h2>
<p>This project consists of installing and using Wireshark to capture and analyze packets along with utilizing various display filters to optimize capture results.</p>



<h2>Languages and Utilities Used</h2>

- <b>Linux Terminal</b>
- <b>Wireshark</b>
- <b>Web Browser</b> 

<h2>Environments Used </h2>

- <b> Ubuntu</b> 

<h2>Objectives:</h2>

- <b>Install Wireshark on Ubuntu and set up Wireshark for non super users belonging to the Wireshark group.</b> 
- <b>Start a capture while visiting web pages.</b>
- <b>Save capture to a file.</b> 
- <b>Use display filters to detect HTTP and HTTPS packets.</b> 
- <b>Analyze packets to identify destination IP, source IP, transmission control protocol, source port, destination port and packet length.</b> 
- <b>Use an IP address filter to only show capture results from a specific IP address.</b> 
- <b>Use TLS handshake filter in order to only display TLS packets.</b>
- <b>Add conditional statements to a display filter to allow Wiresahrk to include or exclude particular packets from the capture.</b>

<h2>Program walk-through:</h2>

<p align="center">
Install Wireshark: <br/>
<img src="https://i.imgur.com/tOhv4GD.png" alt="Vulnerability Scanning With Nmap"/>
<br />
<br />
 Access help feature: <br/>
<img src="https://i.imgur.com/6VD93Gq.png" height="80%" width="80%" alt="Vulnerability Scanning With Nmap"/>
<br />
<br />
  Access man page: <br/>
<img src="https://i.imgur.com/tqvE67t.png" height="80%" width="80%" alt="Vulnerability Scanning With Nmap"/>
<br />
<br />
   Use man page to reference scan type: <br/>
<img src="https://i.imgur.com/HDNhdOr.png" height="80%" width="80%" alt="Vulnerability Scanning With Nmap"/>
<br />
<br />
Run a basic network scan:  <br/>
<img src="https://i.imgur.com/Em91bfx.png" height="80%" width="80%" alt="Vulnerability Scanning With Nmap"/>
<br />
<br />
Run an aggressive scan:  <br/>
<img src="https://i.imgur.com/2eBa5VM.png" height="80%" width="80%" alt="Vulnerability Scanning With Nmap"/>
<br />
<br />

</p>

<h2>Findings:</h2>

- <b> Wireshark is a very useful tool that can capture and analyze traffic throughout a network.</b> 
- <b> Wireshark can be used to analyze packets to help identify various data types including destination IP, source IP, transmission control protocol, source port, destination port and packet length.</b>
- <b> The IP address filter (ip.addr==) can be useful for obtaining packet information for particular web sites.</b>
- <b> The TLS handshake filter (tls.handshake.type==1) can be used to detect a website that was succesfully visited within a packet list.</b>
- <b> Adding conditional statements to your filter can be helpful when you want to include or exclude packets or packet types from a capture.</b> 
- <b> Wireshark typically should not run as a super user for security reasons.</b> 



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
