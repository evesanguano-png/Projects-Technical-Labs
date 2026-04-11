# Lab 01 — VLSM Subnetting Design and Implementation

## Description
Design and implementation of a VLSM addressing scheme over the `172.31.103.0/24` network,
divided into 4 subnets based on host requirements per area.

Full configuration of routers and switches with end-to-end connectivity verification.

**Tool:** Cisco Packet Tracer  
**Course:** Cisco Networking Academy — CCNA  
**Completion:** 100% ✓

---

## Network Topology
The network has the following requierements:
- Room 114 LAN will requiere 27 host IP addresses
- Room 279 LAN will requiere 25 host IP addresses
- Room 312 LAN will requiere 14 host IP addresses
- Room 407 LAN will requiere 8 host IP addresses

![image_alt](https://github.com/evesanguano-png/Projects-Technical-Labs/blob/de13024f1d5b68d1e66d359bef1fa750df75d7a8/LAB1-CAP%201.png)

---

## VLSM Subnet Table

![image_alt](https://github.com/evesanguano-png/Projects-Technical-Labs/blob/de13024f1d5b68d1e66d359bef1fa750df75d7a8/LAB1-CAP2.png)

---

## Connectivity Verification

Connectivity verified from Branch1, Room-312, and PC-D using ping to all addresses in the addressing table.

![image_alt](https://github.com/evesanguano-png/Projects-Technical-Labs/blob/de13024f1d5b68d1e66d359bef1fa750df75d7a8/LAB1-CAP3.png)

---

## Skills Demonstrated

- Variable Length Subnet Masking (VLSM)
- Subnet calculation: network address, first host, broadcast
- Cisco IOS interface configuration on routers
- Default gateway assignment on switches and hosts
- End-to-end connectivity testing

---
## Credits
Lab based on Cisco Networking Academy curriculum (CCNA).  
Topology and network requirements are part of the course material.  
Solution, configuration, and documentation are my own work.
