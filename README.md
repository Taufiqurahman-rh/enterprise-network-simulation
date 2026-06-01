## Enterprise Network Simulation

An enterprise network simulation built with Cisco Packet Tracer,
replicating a real-world multi-site data center infrastructure.

## Description
This project simulates a multi-site enterprise network with security 
policies across segments, using 4 routers, 4 switches, 4 DNS servers, 
and 19+ client PCs distributed across 4 server racks.

## Features
- Multi-router architecture connecting 4 sites via fiber links
- Dynamic Routing using RIP v2
- Load Balancing & Failover across redundant links
- ACL-based security: each VLAN is blocked from accessing 
  its own local DNS Server
- Distributed DNS Servers across all sites
- Centralized DHCP with per-VLAN configuration
- VLAN Segmentation using IEEE 802.1Q trunking

## Protocols
RIP v2 | DNS | DHCP | ACL | IEEE 802.1Q

##  Tools
Cisco Packet Tracer
