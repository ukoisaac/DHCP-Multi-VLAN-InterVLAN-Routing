# DHCP Server for Multiple VLANs + Inter-VLAN Routing

## Project Overview
This lab demonstrates how to configure:

- Multiple VLANs
- Inter-VLAN Routing
- DHCP for multiple VLANs
- Trunk Links
- Multilayer Switching
- End-to-End Connectivity

## Network Topology

<img width="1344" height="732" alt="DHCP SERVER FO MULTIPLE VLANS   DHCP and  Routing" src="https://github.com/user-attachments/assets/a4ae56a1-b2b0-44c5-9efb-d0b0c9e4c782" />

---

## VLAN Configuration

| Department | VLAN | Network |
|---|---|---|
| IT | VLAN 10 | 192.168.1.0/24 |
| FIN | VLAN 20 | 192.168.2.0/24 |
| HR | VLAN 30 | 192.168.3.0/24 |

---

## Technologies Used

- Cisco Packet Tracer
- VLANs
- Trunking
- DHCP
- Inter-VLAN Routing
- Multilayer Switch

---

## Key Configurations

### VLAN Creation
- VLAN 10 → IT
- VLAN 20 → FIN
- VLAN 30 → HR

### Trunk Ports
Configured trunk links between switches and multilayer switch.

### DHCP Configuration
Configured DHCP pools for all VLANs.

### Inter-VLAN Routing
Enabled routing on multilayer switch using SVIs.

---

## Verification Commands

```bash
show vlan brief
show interfaces trunk
show ip interface brief
show ip route
show ip dhcp binding
