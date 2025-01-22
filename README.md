# Secure Enterprise Network Simulation

This project demonstrates the design, configuration, and troubleshooting of a secure enterprise network using **Cisco Packet Tracer**. It incorporates VLANs, ACLs, VPN tunnels, port security, and other best practices to simulate a real-world secure network environment.

Please download "WAN Project.pkt" to navigate the Network!

---

## Project Overview
The network is segmented into multiple zones, each with distinct IP addressing and security configurations. Key features include:
- **VLAN Segmentation** for traffic isolation and broadcast control.
- **Access Control Lists (ACLs)** to restrict unauthorized access.
- **VPN Tunnels** for secure data transfer between remote offices.
- **Port Security** to prevent unauthorized device connections.
- **SYSLOG Servers** for centralized event logging and analysis.

---

## Key Features

### 1. Network Topology
The topology includes:
- R&D Network: `10.0.0.x/8` (Green Zone)
- DMZ Network: `192.168.230.x/24` (Yellow Zone)
- Server Network: `192.168.90.x/24` (Red Zone)
- Corporate Network: `172.16.230.x/27` (Blue Zone)
- Remote Office: `172.16.90.x/24` (Pink Zone)

**Key Devices:**
- Routers, Layer 2 and Layer 3 Switches
- Servers (Web, DNS, FTP, SYSLOG)
- End Devices (Workstations, DHCP, and File Servers)

---

### 2. Security Implementations
- **VLAN Segmentation:** Logically separated traffic to improve performance and security.
- **ACLs:** Configured to control and restrict traffic flow.
- **Port Security:** Sticky MAC addresses to prevent unauthorized access.
- **VPN Tunnel:** Secure communication between the main network and the remote office.
- **SYSLOG Server:** Real-time event monitoring and logging for easier troubleshooting.
- **Static Routing:** Defined predictable and controlled traffic flow.

---

### 3. Troubleshooting Process
The following simulated issues were identified and resolved:
- **VLAN Misconfigurations:** Fixed trunk and VLAN assignments to restore connectivity.
- **ACL Blockages:** Reviewed and simplified ACL rules.
- **Port Errors:** Reconfigured malfunctioning ports and replaced simulated devices.
- **VPN Configurations:** Ensured encrypted tunnels functioned as intended.

---

## Visual Representation
### Network Topology:
![{70B84021-90B6-4183-BA8B-73F25BC7FC61}](https://github.com/user-attachments/assets/864c28cf-86f2-4925-89e6-1e10c5967207)

The network is divided into multiple zones with clear IP segmentation and security configurations.

---

## Tools & Technologies
- **Cisco Packet Tracer** – For network design and simulation.
- **SYSLOG Servers** – For event monitoring and logging.
- **Static Routing & VLANs** – For segmented and optimized traffic flow.
- **VPN Protocols** – For secure inter-network communication.

---

## How to Use
1. Download the **Packet Tracer file** (`MBurns_SecureNetwork_A2.pkt`).
2. Open the file using **Cisco Packet Tracer**.
3. Review and test configurations on routers, switches, and devices.
4. Explore VLANs, ACLs, port security, and static routes to understand the setup.

---

## Outcomes
This project demonstrates practical implementation and troubleshooting of:
- **Secure network design** principles.
- **Traffic segmentation and control** using VLANs and ACLs.
- **Real-world troubleshooting** methods for connectivity and configuration issues.

---

## Key Learnings
- Network segmentation enhances both performance and security.
- ACLs and Port Security are vital for controlling unauthorized access.
- VPNs ensure data integrity and privacy over untrusted networks.

---
## IP Tables

### Host Devices
![{5226FDA2-7EB5-40C3-B4DE-F7BFB3242671}](https://github.com/user-attachments/assets/d834594f-bc68-426c-bb06-72d5b1c13be3)
![{CE87F55D-C93D-4D18-BC23-876D046C0A89}](https://github.com/user-attachments/assets/4ad57c43-d873-4868-b576-e7f3923c985f)

### Network Devices
![{49844245-5F6F-4E51-847F-3DC4DD9B5BFB}](https://github.com/user-attachments/assets/b2b6ad31-53f8-4fb5-90a4-399f933608e9)

### Security Configurations
![{0FFE7F5A-A344-45AB-8ED4-05BA1AFDA4CF}](https://github.com/user-attachments/assets/041e9f2a-e03c-4562-b44b-7a115e25554c)

---

Feel free to download this project or use it as a reference for implementing secure enterprise networks in **Cisco Packet Tracer**.
