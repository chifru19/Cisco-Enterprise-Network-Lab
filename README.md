# Cisco-Enterprise-Network-Lab
A Cisco Packet Tracer lab featuring OSPF, Inter-VLAN routing, and Layer 2 security."
# Enterprise Network Design & Security Lab
A professional Cisco Packet Tracer implementation featuring OSPF, Inter-VLAN routing, and hardened Layer 2 security.

## 🚀 Key Implementations
* **OSPF Dynamic Routing**: Configured Area 0 for automated route discovery between HQ and Branch.
* **Layer 2 Security**: Implemented Port Security with `sticky` MAC addresses and `violation shutdown` on access ports.
* **VLAN Management**: Created Management and Staff segments using IEEE 802.1Q encapsulation.
* **Secure Management**: Deployed SSH v2 for encrypted remote device access.

## 🛠️ Troubleshooting Spotlight
During this lab, we explored **EtherChannel (LACP/PAgP)** implementation. While physical links were successfully bundled, we navigated hardware limitations regarding sub-interface support on the 2911 router model, ultimately optimizing for a high-performance single-trunk design to ensure 100% uptime.

## 📊 Topology
![Network Topology](./Screenshot 2026-02-22 at 11.55.40.jpg)
