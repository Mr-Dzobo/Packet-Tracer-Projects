# Packet Tracer Projects

## Project 1 — Inter-VLAN Routing with a Layer 3 Switch

### Topology
- 1x Cisco 3650 Layer 3 Switch
- 2x Cisco 2960 Layer 2 Switches
- 6x Laptops (3 per department)

### Departments
- Administration — VLAN 10 (192.168.10.0/24)
- FOCIS — VLAN 20 (192.168.20.0/24)

### What this project covers
By default VLANs are isolated from each other. 
This project configures inter-VLAN routing so that 
devices across different departments can communicate 
through a Layer 3 switch.

### Concepts configured
- VLAN creation on all switches
- Access port assignment
- Trunk links (802.1Q)
- Switched Virtual Interfaces (SVIs)
- IP routing on Layer 3 switch

### Verification
Successful pings between Administration 
and FOCIS laptops across VLANs.

## Update 1 — Added ESA Department (VLAN 30)

### Changes made
- Added VLAN 30 (ESA_Department) to all switches
- Connected 3 laptops via new Cisco 2960 Layer 2 switch
- Configured access ports Fa0/1-3 on ESA switch
- Updated trunk links to allow VLAN 30
- Created SVI on Layer 3 switch (192.168.30.1)

### Verification
Successful pings between ESA and all other departments.
