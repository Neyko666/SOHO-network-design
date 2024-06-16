# SOHO-network-design
After 2 hours configuration I completed a SOHO network design and implementation project on Cisco Packet Tracer.

Technology Implemented:

1.IP subnetting and addressing. I used 192.168.1.0/24 to divided into 3 subnets of /26 for three departments as shown on topology.

2.VLAN. I created 3 vlans for three departments and configured them on corresponding access ports on S1.

3.Spanning Tree Portfast. I configured Portfast on all edge ports of S1 facing host devices for layer 2 security.

4.Trunk. I configured link between R1 and S1 as trunk link and only allowed traffic from 3 internal departments to pass through.

5.DHCP. I configure DHCP on R1 to made it act as DHCP server and made it automatically assign IPs to all host devices in the office including PCs, laptops, printers and smart phones.

6.Wireless access points. I configured SSID and WPA2 password on three APs and also made Laptops and smartphones connecting to the AP of their own departments.

7.Connection Test. I tested connection between 3 departments and all of them can communicate with each other in the office.

![1717058922308](https://github.com/Neyko666/SOHO-network-design/assets/171580092/e1adaa0a-69c8-4cbc-9a81-737072729dc7)
![e0535e8446a1cc8641659f6c61dfcf8](https://github.com/Neyko666/SOHO-network-design/assets/171580092/53d2aec7-fc54-410d-ba51-235d80181ef4)
![4f827472e4a3bd069bee27bc13c5192](https://github.com/Neyko666/SOHO-network-design/assets/171580092/cc2c66de-317f-49d1-af61-c6d603ecb353)
![951961f9b77360e67139db19b710e8f](https://github.com/Neyko666/SOHO-network-design/assets/171580092/5297ce74-95c0-48a0-ab4f-a2467d0b4392)
![Uploading 186a0827c03e31cfd65b2b5b7c0b577.jpg…]()
