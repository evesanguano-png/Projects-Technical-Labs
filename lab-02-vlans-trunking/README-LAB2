# Lab 02 — VLANs and Trunking Implementation

## Description
Configuration and verification of VLANs and trunk links across three 2960 switches.
Includes access port assignment, voice VLAN setup, static and dynamic trunking,
and virtual management interfaces (SVI).

**Tool:** Cisco Packet Tracer  
**Course:** Cisco Networking Academy — CCNA  
**Completion:** 100% ✓

---

## Network Topology

![Network Topology](LAB2-CAP1.png)

---

## VLAN Table

| VLAN | Name       |
|------|------------|
| 10   | Admin      |
| 20   | Accounts   |
| 30   | HR         |
| 40   | Voice      |
| 99   | Management |
| 100  | Native     |

---

## Addressing Table

| Device | Interface | IP Address      | Subnet Mask     | VLAN        |
|--------|-----------|-----------------|-----------------|-------------|
| PC1    | NIC       | 192.168.10.10   | 255.255.255.0   | VLAN 10     |
| PC2    | NIC       | 192.168.20.20   | 255.255.255.0   | VLAN 20     |
| PC3    | NIC       | 192.168.30.30   | 255.255.255.0   | VLAN 30     |
| PC4    | NIC       | 192.168.10.11   | 255.255.255.0   | VLAN 10     |
| PC5    | NIC       | 192.168.20.21   | 255.255.255.0   | VLAN 20     |
| PC6    | NIC       | 192.168.30.31   | 255.255.255.0   | VLAN 30     |
| PC7    | NIC       | 192.168.10.12   | 255.255.255.0   | VLAN 10/40  |
| SWA    | SVI       | 192.168.99.252  | 255.255.255.0   | VLAN 99     |
| SWB    | SVI       | 192.168.99.253  | 255.255.255.0   | VLAN 99     |
| SWC    | SVI       | 192.168.99.254  | 255.255.255.0   | VLAN 99     |

---

## Verification
# VLAN and Trunk Verification -SWA
![VLAN and Trunk Verification ](LAB2-CAP2.png)

# Dynamic Trunking Verification -SWC (DTP)

G0/2 on SWA configured to successfully negotiate trunking with SWC using DTP.

![Dynamic Trunk SWC G0/2](LAB2-CAP3.png)
---

## Skills Demonstrated

- VLAN creation and naming on Cisco 2960 switches
- Access port assignment per VLAN
- Voice VLAN configuration (VLAN 40)
- Static trunking with DTP disabled (SWA–SWB)
- Dynamic trunking negotiation (SWA–SWC)
- Native VLAN configuration to eliminate conflicts
- SVI configuration for remote switch management

---

## Credits
Lab based on Cisco Networking Academy curriculum (CCNA).  
Topology and network requirements are part of the course material.  
Solution, configuration, and documentation are my own work.
