<h1 align="center">
CIDR Notation Tutorial</h1>

 ### [CIDR Notation YouTube Demonstration](https://youtu.be/BSHLd8JC-TA)

<h2>Description</h2>
This is an in depth Tutorial explaining CIDR Notation.
<br />

<h2>Definition</h2>
<img src="https://i.imgur.com/Ey2Wll5.png" height="80%" width="80%" align="center" alt="CIDR NOTATION PICTURE"/>

<p> CIDR notation compactly indicates the network mask for an address and adds on the total number of bits in the entire address using slash notation. </p>


<h2 align="center">Programs or Utilities Used</h2>

<p align="center">- <b>Miro Whiteboard</b> </p>


<h2 align="center">Environments Used </h2>

<p align="center">- <b align="center">Windows 10</b> </p>

<h2 align="center">Tutorial</h2>

<p align="center">
 <br/>
<img src="https://i.imgur.com/QwkIjFL.jpg" height="80%" width="80%"/>
 <p><b> CIDR notation or Classless Inter-Domain Routing is an alternate method of representing a subnet mask. It is a count of the number of network bits that are set to in the subnet mask. Every IPV4 address has a 32 bit bianry value that are broken down into 8 bit chunk octets. In simpler terms, CIDR notation is a way to write IP address ranges using a shorthand notation, so that we can write a whole range of IP addresses with a single notation.</b> </p> 
<br />
<br />
<br/>
<p align="center">
<img src="https://i.imgur.com/M0wisXg.jpg" height="80%" width="80%"/>
  <p><b> Every bit has a corresponding bit weight. A "1" in the corresponding bit "box", activates the bit weight. </b></p>
<br />
<br />
<br/>
<p align="center">
<img src="https://i.imgur.com/vgEdwul.jpg" height="80%" width="80%"/>
 <p><b> Be sure to add the activated bit weights toghether because the sum of the bit weight is the IP address . </b></p>
 
<br />
<br />

<p align="center">
<img src="https://i.imgur.com/ZXhLNou.jpg" height="80%" width="80%"/>
 <p><b> In this example, the subnet mask(255) is pointing(purple line) to the first two octects. There are 8 bits in every octect, and because the subnet mask
  255 is only activated in the first two octects, in this example, the slash notation is "/16". 255 represent which portion of the IP address is the network's address and the rest of the IP address belongs to the host.</b></p>

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
