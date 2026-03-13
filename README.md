# LAN-Setup-and-Configuration
This project demonstrates the setup of a Local Area Network (LAN) using Cisco Packet Tracer. Multiple systems are connected through a switch, IP addresses are configured, and connectivity is tested using ping. The project helps understand basic networking concepts and device communication in a local network environment. 
🛠 Tools Used
Cisco Packet Tracer 
🌐 Network Topology
Devices used in the network:
3 PCs
1 Switch (Cisco 2960)
1 Printer
1 FTP Server
All devices are connected to a central switch, forming a Star Topology LAN network. 
💻 IP Address Configuration
| Device  | IP Address    | Subnet Mask   |
| ------- | ------------- | ------------- |
| PC0     | 192.168.1.1   | 255.255.255.0 |
| PC1     | 192.168.1.2   | 255.255.255.0 |
| PC2     | 192.168.1.3   | 255.255.255.0 |
| Printer | 192.168.1.10  | 255.255.255.0 |
| Server  | 192.168.1.100 | 255.255.255.0 |
⚙ Network Configuration 
The network was configured by connecting all devices to a switch using copper straight-through cables. Each device was assigned a unique IP address within the same subnet to allow communication within the LAN.
🧪 Network Testing 
Network connectivity was verified using the ping command. 
ping 192.168.1.2
ping 192.168.1.3
ping 192.168.1.10 
Successful replies confirmed that all devices were communicating properly within the network. 
📂 FTP Server Access 
An FTP server was accessed from a PC using the following command: 
ftp 192.168.1.100 
After login, the directory listing was displayed, confirming that the FTP service was active in the network. 
📷 Network Topology Screenshot 
See network-topology.png for the visual representation of the network created in Cisco Packet Tracer. 
🎯 Conclusion 
This project demonstrates the basic setup of a Local Area Network using Cisco Packet Tracer. It helped in understanding device connectivity, IP address configuration, network communication, and basic network services within a LAN environment. 
