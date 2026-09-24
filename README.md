# CCNA Enterprise Network Project

## 📌 Project Overview

This project is a complete enterprise network simulation created using
Cisco Packet Tracer as part of CCNA practical learning.

The project demonstrates VLANs, trunking, Router-on-a-Stick,
inter-VLAN routing, OSPF, DHCP, server connectivity, ACL security,
and network troubleshooting.

---

## 🌐 Network Topology

![CCNA Enterprise Network Topology](topology.png)

### Network Design

PC0 ──┐
       │
PC1 ── SW1 ── R1 ── R2 ── SW2 ──┬── PC2
                                  │
                                Server

---

## 🔧 Technologies Used

- Cisco Packet Tracer
- Cisco IOS
- IPv4
- VLAN
- 802.1Q Trunking
- Router-on-a-Stick
- OSPF
- DHCP
- ACL
- Static Routing
- Network Troubleshooting

---

## 🏢 VLAN Configuration

| VLAN | Name | Network |
|------|------|---------|
| 10 | HR | 192.168.10.0/24 |
| 20 | IT | 192.168.20.0/24 |

### VLAN 10

Gateway:

```text
192.168.10.1
