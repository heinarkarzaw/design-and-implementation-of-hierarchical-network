# Hierarchical Netwrork Design
## Description
This project presents a comprehensive hierarchical network design that emphasizes modularity, scalability, and flexibility. The design includes multilayer switches, core routers, redundant ISP connections, and VLAN segmentation for four departments (D1, D2, D3, D4). The network is built with high-availability, security, and efficient routing in mind, using technologies such as EtherChannel, HSRP, OSPF, DHCP, DNS, and more.

## Key Features
- Modular Design: The network is designed to easily scale and adapt as future growth demands increase.
- Redundant Connections: Redundant EtherChannel and core router connections ensure high availability and resilience in case of failures.
- VLAN Segmentation: Each department (D1, D2, D3, D4), the server room, and Wireless LAN Controller (WLC) have their own VLANs, providing clear separation and improved network performance.
- Inter-VLAN Routing: Configured on multilayer switches, enabling communication between different VLANs for seamless data transfer.
- Dynamic Routing with OSPF: The network uses OSPF to efficiently route traffic across the network backbone.
- High Availability with HSRP: Hot Standby Router Protocol (HSRP) is implemented for redundancy and seamless failover between multilayer switches.
- Server Room: The server room hosts critical infrastructure services including DHCP, DNS, Email, and Web servers.
- Wireless LAN Management: A centralized Wireless LAN Controller (WLC) manages access points across all departments.
- SSH Access Control: SSH is used for secure remote access to network devices.
- ACLs for Security: Standard Access Control Lists (ACLs) restrict unauthorized access and enforce Network Address Translation (NAT) for external communication.
- Spanning Tree Protocol Enhancements: Spanning Tree PortFast and BPDU Guard are configured on access ports to ensure a loop-free network.

## Simulation Software
- Cisco Packet Tracer
