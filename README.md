# SOHO-network-design
A SOHO network design and implementation project on Cisco Packet Tracer. The office has three departments.

Technology Implemented:

1.IP subnetting and addressing. I used 192.168.1.0/24 to divided into 3 subnets of /26 for three departments as shown on topology.

2.VLAN. I created 3 vlans for three departments and configured them on corresponding access ports on S1.

3.Spanning Tree Portfast. I configured Portfast on all edge ports of S1 facing host devices for layer 2 security.

4.Trunk. I configured link between R1 and S1 as trunk link and only allowed traffic from 3 internal departments to pass through.

5.DHCP. I configure DHCP on R1 to made it act as DHCP server and made it automatically assign IPs to all host devices in the office including PCs, laptops, printers and smart phones.

6.Wireless access points. I configured SSID and WPA2 password on three APs and also made Laptops and smartphones connecting to the AP of their own departments.

7.Connection Test. I tested connection between 3 departments and all of them can communicate with each other in the office.

Pkt file in directory.

<div align = "center">
<img src="https://github.com/Neyko666/SOHO-network-design/assets/171580092/fe4225c5-47d6-467e-89b9-6590501bdbd2" width="800">
</div>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/SOHO-network-design/assets/171580092/06cc24e6-21fb-45d6-bb7a-ba738f9e3f6a" width="500">
</div>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/SOHO-network-design/assets/171580092/b4cd4cf1-c62d-4e71-8999-99d18639b750" width="500">
</div>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/SOHO-network-design/assets/171580092/d2243665-1a7d-4a05-8e6b-35bca0f2afd3" width="500">
</div>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/SOHO-network-design/assets/171580092/15313c51-f1bc-4872-867d-c64befaa50db" width="500">
</div>


