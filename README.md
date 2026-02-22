# Cisco Enterprise Network Lab

A comprehensive Cisco Packet Tracer implementation featuring dynamic routing, secure VLAN management, and hardened Layer 2 security.

## 🌐 Network Topology
![Network Topology](Screenshot%202026-02-22%20at%2012.20.20.png)

### 🎓 Skills Learned
* **Advanced CLI Proficiency:** Expert navigation of Cisco IOS for device configuration and troubleshooting.
* **Security Hardening:** Protecting network infrastructure using Port Security (Sticky MAC) and SSH v2.
* **Dynamic Routing Protocols:** Configuring and optimizing OSPF (Area 0) for efficient data path discovery.
* **VLAN & Trunking (802.1Q):** Segmenting broadcast domains and configuring trunks for Inter-VLAN routing.

### 🌐 Network Architectures
I have demonstrated an understanding of different network architectures and how they apply to enterprise environments:

![Network Architectures](network_types.jpg)

* **Client-Server Model:** Centralized management, high scalability, and enhanced security for enterprise use.
* **Peer-to-Peer (P2P):** Decentralized connectivity best suited for small, simple environments.

### 🛠️ Troubleshooting Spotlight
During this lab, we explored **EtherChannel (LACP/PAgP)** implementation. While physical links were successfully bundled, we navigated hardware limitations regarding sub-interface support on the **2911 router** model, ultimately optimizing for a high-performance single-trunk design to ensure 100% uptime.

### 📂 Project Files
* **[Full_Lab_Configs.txt](./Full_Lab_Configs.txt):** Contains the complete running configurations for both Router0 and Switch0.
### ✅ Testing & Verification
To ensure the network was operating correctly, I performed connectivity tests between segments.

* **Local Success:** Successfully pinged the local gateway and internal hosts (e.g., `192.168.10.2`).
* **Inter-VLAN Connectivity:** Verified communication between Management and Staff VLANs via the Router-on-a-Stick configuration.

### ✅ Testing & Verification
To ensure the network was operating correctly, I performed connectivity tests between segments.

* **Local Success:** Successfully pinged the local gateway and internal hosts (e.g., `192.168.10.2`).
* **Inter-VLAN Connectivity:** Verified communication between Management and Staff VLANs.

![Ping Test Results](ping_test.png.)

> **🔍 Troubleshooting Note:** In the results above, the timeout to `192.168.20.1` was identified as an ARP resolution delay. Subsequent tests confirmed 100% connectivity after the routing table converged.
