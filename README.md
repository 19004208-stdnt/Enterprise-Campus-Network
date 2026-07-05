# Enterprise Campus Network Infrastructure

## Project Overview
This project demonstrates the design and implementation of an enterprise campus network using Cisco Packet Tracer. The network follows Cisco's three-tier hierarchical architecture: Core, Distribution, and Access layers.

The project includes VLAN segmentation, inter-VLAN routing, enterprise switching, firewall integration, IP addressing, and network testing.

## Network Architecture
- ISP Cloud
- Cisco 2911 Edge Router
- Cisco ISA-3000 Firewall
- Cisco 3650 Core Switch
- Cisco 3560 Distribution Switches
- Cisco 2960 Access Switches
- Department PCs and Printers
- Data Centre Server Network

## Departments
- Administration
- ICT
- Engineering
- Science
- Library
- Student Residence
- Data Centre

## Technologies Used
- Cisco Packet Tracer
- VLANs
- 802.1Q Trunking
- Inter-VLAN Routing
- Cisco IOS CLI
- IP Addressing
- Static Routing
- Firewall Configuration
- Network Troubleshooting

## Skills Demonstrated
- Enterprise Network Design
- Routing and Switching
- VLAN Configuration
- Trunk Port Configuration
- Firewall Integration
- IP Address Planning
- Network Testing
- Cisco CLI Configuration
- Technical Documentation

## Network Topology
![Physical Topology](diagrams/Physical%20Topology.png)

## VLAN and IP Addressing Plan

| VLAN | Department | Network | Gateway |
|------|------------|---------|---------|
| 10 | Administration | 192.168.10.0/24 | 192.168.10.1 |
| 20 | ICT | 192.168.20.0/24 | 192.168.20.1 |
| 30 | Engineering | 192.168.30.0/24 | 192.168.30.1 |
| 40 | Science | 192.168.40.0/24 | 192.168.40.1 |
| 50 | Library | 192.168.50.0/24 | 192.168.50.1 |
| 60 | Residence | 192.168.60.0/24 | 192.168.60.1 |
| 100 | Servers | 192.168.100.0/24 | 192.168.100.1 |

## Testing
The network was tested using:
- Ping tests
- Trunk verification
- VLAN verification
- Interface status checks
- Firewall interface verification

## Future Improvements
- DHCP Server
- DNS Server
- Web Server
- Email Server
- File Server
- ACLs
- NAT
- OSPF
- Port Security
- Wireless Network
- Network Monitoring
