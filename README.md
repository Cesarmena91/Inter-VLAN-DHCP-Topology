# VLAN + DHCP Lab (Cisco Packet Tracer)

This lab demonstrates:
- VLAN segmentation (VLAN 10, 20, 30)
- Inter-VLAN routing using router-on-a-stick
- Centralized DHCP server using `ip helper-address`

## 🖧 Topology Overview
- VLAN 10: Management (10.0.0.0/24)
- VLAN 20: Sales (10.0.1.0/24)
- VLAN 30: Engineering (10.0.2.0/24)
- Router subinterfaces: 10.0.0.254, 10.0.1.254, 10.0.2.254, 10.0.3.254
- DHCP Server IP: 10.0.3.1

## 🔧 Technologies Used
- Cisco Packet Tracer
- Static routing
- DHCP relay
- VLAN trunking and access ports

## ▶️ How to Run
1. Open the `.pkt` file in Cisco Packet Tracer
2. Power on devices if needed
3. Watch PCs receive IPs via DHCP from the centralized server

## 📂 Files Included
- `VLAN_DHCP_Lab.pkt` – Main lab topology
