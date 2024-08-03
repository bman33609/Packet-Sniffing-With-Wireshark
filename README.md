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
- <b>Use display filters to detect HTTP and HTTPS packets.</b> 
- <b>Analyze packets to identify destination IP, source IP, transmission control protocol, source port, destination port and packet length.</b> 
- <b>Use an IP address filter to only show capture results from a specific IP address.</b> 
- <b>Use TLS handshake filter in order to only display TLS packets.</b>
- <b>Add conditional statements to a display filter to allow Wireshark to include or exclude particular packets from the capture.</b>
- <b>Save capture to a file.</b> 

<h2>Program walk-through:</h2>

<p align="center">
Install Wireshark: <br/>
<img src="https://i.imgur.com/fu2wwyK.png" height="80%" width="80%" alt="Packet Sniffing With Wireshark"/>
<br />
<br />
   For this excercise we will be capturing packets from the ethernet port: <br/>
<img src="https://i.imgur.com/TiV63M7.png" height="80%" width="80%" alt="Packet Sniffing With Wireshark"/>
<br />
<br />
   Start a basic capture: <br/>
<img src="https://i.imgur.com/nfLfsVw.png" height="80%" width="80%" alt="Packet Sniffing With Wireshark"/>
<br />
<br />
  Use display filter to detect HTTPS packets: <br/>
<img src="https://i.imgur.com/PPkzRfe.png" height="80%" width="80%" alt="Packet Sniffing With Wireshark"/>
<br />
<br />
   Use IP address filter to only display packets from a specific IP address: <br/>
<img src="https://i.imgur.com/3MHizlX.png" height="80%" width="80%" alt="Packet Sniffing With Wireshark"/>
<br />
<br />
  Filter your capture to only display packets that exclude a specific IP address:<br/>
<img src="https://i.imgur.com/WdKoMS8.png" height="80%" width="80%" alt="Packet Sniffing With Wireshark"/>
<br />
<br />
Examine packet for various data including destination IP, source IP, source port and packet length:  <br/>
<img src="https://i.imgur.com/hgbX3FV.png" height="80%" width="80%" alt="Packet Sniffing With Wireshark"/>
<br />
<br />
 Use a destination IP filter:</br>
<img src="https://i.imgur.com/RoNRXHc.png" height="80%" width="80%" alt="Packet Sniffing With Wireshark"/>
<br />
<br />
  Use a source IP filter:</br>
<img src="https://i.imgur.com/Xavlhys.png" height="80%" width="80%" alt="Packet Sniffing With Wireshark"/>
<br />
<br />
 Now, lets try a TLS handshake filter:</br>
<img src="https://i.imgur.com/IH2jrBu.png" height="80%" width="80%" alt="Packet Sniffing With Wireshark"/>
<br />
<br />
 Finally, we should always save our captures to a file for future reference or for potential audits:</br>
<img src="https://i.imgur.com/L732cWT.png" height="80%" width="80%" alt="Packet Sniffing With Wireshark"/>
<br />
<br />
</p>

<h2>Findings:</h2>

- <b> Wireshark is a very useful tool that can capture,analyze and monitor traffic throughout a network.</b> 
- <b> Wireshark can be used to analyze packets to help identify various data types including destination IP, source IP, transmission control protocol, source port, destination port and packet length.</b>
- <b> The IP address filter (ip.addr==) can be useful for obtaining packet information for particular web sites.</b>
- <b> The TLS handshake filter (tls.handshake.type==1) can be used to detect a website that was succesfully visited within a packet list.</b>
- <b> Adding conditional statements to your filter can be helpful when you want to include or exclude packets or packet types from a capture.</b> 
- <b> Wireshark typically should not run as a super user for security reasons.</b> 



