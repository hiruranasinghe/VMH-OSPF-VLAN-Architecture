# VMH-OSPF-VLAN-Architecture

## 📌 Overview
This project presents a complete enterprise network design and simulation for **Vic Modern Hotel** using Cisco Packet Tracer. The network is structured across three floors with proper segmentation, dynamic routing, and secure access mechanisms to reflect a real-world organizational infrastructure.

---

## 🏢 Network Structure

### 🟢 Floor 1
- VLAN 80 – Reception → 192.168.8.0/24  
- VLAN 70 – Store → 192.168.7.0/24  
- VLAN 60 – Logistics → 192.168.6.0/24  

### 🔵 Floor 2
- VLAN 50 – Finance → 192.168.5.0/24  
- VLAN 40 – HR → 192.168.4.0/24  
- VLAN 30 – Sales/Marketing → 192.168.3.0/24  

### 🟣 Floor 3
- VLAN 20 – Admin → 192.168.2.0/24  
- VLAN 10 – IT → 192.168.1.0/24  

---

## ⚙️ Technologies Used

- VLANs (Network segmentation)  
- Inter-VLAN Routing (Router-on-a-Stick)  
- OSPF (Dynamic Routing Protocol – Area 0)  
- DHCP (Automatic IP Address Assignment)  
- SSH (Secure Remote Access)  
- Port Security (MAC-based restriction)  
- Wireless Access Points (Wi-Fi connectivity)  

---

## 🔗 Routing Design

Routers are interconnected using serial DCE cables with the following networks:

- 10.10.10.0/30  
- 10.10.10.4/30  
- 10.10.10.8/30  

OSPF is configured to advertise all VLAN networks and enable communication between floors.

---

## 🔐 Security Features

- SSH configured on all routers for secure remote login  
- Port Security enabled on IT department switch:
  - Interface: Fa0/1  
  - Sticky MAC address learning  
  - Violation mode: Shutdown  
- Only the **Test-PC** is allowed to access the secured port  

---

## 🌐 Network Services

- DHCP configured on routers for dynamic IP allocation  
- Wireless networks implemented for each floor  
- Printers assigned to each department  

---

## ✅ Key Achievements

- Successful VLAN segmentation for all departments  
- Full inter-VLAN and inter-floor communication achieved  
- Dynamic IP allocation working across the network  
- OSPF routing ensures scalability and efficiency  
- Secure SSH access tested using Test-PC  

---

## 📸 Screenshots

All project screenshots (topology, VLAN configuration, OSPF routing, SSH testing, etc.) are available in the `images/` folder.

---

## 📂 Project Files

- Packet Tracer file: `VicModernHotel-Network.pkt`  
- Configuration screenshots: available in `images/` folder  

---

## 🚀 Conclusion

This project demonstrates a scalable, secure, and well-structured enterprise network suitable for a modern hotel environment. It integrates core networking concepts such as VLAN segmentation, dynamic routing, automated IP management, and network security.

---

## 👩‍💻 Author

**Hiruni Ranasinghe**  
Undergraduate – Computer Networks  
NSBM University  

---
