# VMH-OSPF-VLAN-Architecture

## 📌 Overview
This project simulates a multi-floor hotel network using Cisco Packet Tracer.  
The network is designed with VLAN segmentation, inter-VLAN routing, dynamic IP assignment, and OSPF routing.

---

## 🏢 Network Structure

### Floor 1
- VLAN 80 – Reception – 192.168.8.0/24
- VLAN 70 – Store – 192.168.7.0/24
- VLAN 60 – Logistics – 192.168.6.0/24

### Floor 2
- VLAN 50 – Finance – 192.168.5.0/24
- VLAN 40 – HR – 192.168.4.0/24
- VLAN 30 – Sales – 192.168.3.0/24

### Floor 3
- VLAN 20 – Admin – 192.168.2.0/24
- VLAN 10 – IT – 192.168.1.0/24

---

## ⚙️ Technologies Used

- VLANs (Network segmentation)
- Inter-VLAN Routing (Router-on-a-Stick)
- OSPF (Dynamic Routing)
- DHCP (Automatic IP assignment)
- SSH (Secure remote access)
- Port Security (MAC-based restriction)
- Wireless Access Points

---

## 🔗 Routing

- OSPF Area 0 used
- Router interconnections:
  - 10.10.10.0/30
  - 10.10.10.4/30
  - 10.10.10.8/30

---

## 🔐 Security Features

- SSH configured on all routers
- Port security enabled on IT switch (Fa0/1)
- Sticky MAC + shutdown violation mode

---

## ✅ Key Achievements

- All VLANs successfully configured
- Inter-floor communication achieved
- DHCP working across all departments
- Secure SSH access tested using Test-PC

---

## 📸 Screenshots

(Insert your images here)

---

## 📂 Files

- Packet Tracer file (.pkt)
- Device configurations
