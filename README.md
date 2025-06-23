<h1>Secure Home Network Deployment - Linux</h1>

<h2>Project Overview</h2>
This project involves setting up and configuring a robust home network, moving from a standard consumer-grade router to a custom-built, server-centric system.<br>
<br>
what is being done and implemented:<br>
<br>

  - A dedicated Rhel derivative Linux server is being set up to act as the central router and firewall for the entire home network.
  - This server will handle all IP address assignments (DHCP) and implement network-wide ad-blocking and content filtering using AdGuard Home (DNS).
  - A Virtual Private Network (VPN) server (WireGuard) is being configured on the Linux server for secure remote access.
  - The network will be logically divided into separate security zones (e.g., a main trusted network and an isolated network for guests and smart home devices) to enhance security and prevent unauthorized access between different types of devices.
  - Network speed is being upgraded with 2.5 Gigabit Ethernet for faster internet and internal data transfers.
  - All network components, configurations, and security measures are being thoroughly documented.

  <h2>💻 Technologies Used 🌐</h2>

| Component Type | Specific Model | Role in Project |
|---|---|---|
| **Hardware** |
| Main Server | Lenovo ThinkCentre M71e SFF PC (Intel Core i5-2400, 8 GB RAM) | Serves as the central router and firewall; hosts all primary network services (DHCP, DNS, VPN). |
| Network Interface Card (NIC) | TP-Link TX201 2.5 Gigabit PCIe Network Adapter | Provides high-speed 2.5 Gigabit Ethernet connectivity for the WAN/LAN connection on the server. | 
| Wireless Access Point | ASUS RT-AC68U Wireless Router | Reconfigured to operate in Access Point (AP) mode, providing Wi-Fi connectivity (2.4 GHz & 5 GHz) for all wireless clients. |
| Internet Modem | Technicolor TC4350 | Interfaces with the Internet Service Provider (ISP) to deliver the primary internet connection. |                                                                            |
    
    
