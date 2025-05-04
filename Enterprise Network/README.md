# 🌐 ICT1013 Computer Network Project – IT Learning Hub Infrastructure

[![Cisco Packet Tracer](https://img.shields.io/badge/Simulator-Cisco%20Packet%20Tracer-blue)](https://www.netacad.com)
[![Miro](https://img.shields.io/badge/Diagram-Miro-yellow)](https://miro.com)
[![School Project](https://img.shields.io/badge/Project-Type:%20Academic-red)]()

## 📘 About the Project

This repository contains the network design and documentation for the **ICT1013 Group Project**, which involves building a **robust enterprise LAN** for a fictional IT Learning Hub aligned with the **UN 2030 Agenda for Sustainable Development**.

The project simulates a **3-tier architecture** using **Cisco Packet Tracer**, enabling:
- Redundant **internet connectivity**
- Segmented departmental and lab **VLANs**
- Efficient routing with **OSPF v2**, **HSRP**, and **Static Routes**
- **Web & DNS services** hosted internally and externally via NAT

> ⚙️ The goal was to support real-world infrastructure needs such as:
- Computer labs 🖥️
- Staff workstations 👩‍💼👨‍🏫
- Internet and DNS/Web Services 🌐
- Scalable and fault-tolerant connectivity 📡

---

## 🛠️ Technologies & Tools Used

| Category       | Tools / Protocols                          |
| ------------- | ------------------------------------------- |
| Simulator     | Cisco Packet Tracer                        |
| Design Tool   | Miro.com                                   |
| Routing       | OSPFv2, Static Routing, HSRP               |
| Addressing    | VLSM, NAT (PAT/Overload), DHCP             |
| Switching     | VLANs, EtherChannel (PAGP), STP            |
| Services      | DNS (Authoritative & Caching), Web Server |
| OS/Stack      | XAMPP, Windows 10 (Simulated Host)         |
| AI Assistant  | ChatGPT (for clarification/documentation)  |

---

## 🧠 Project Highlights

- 📶 **Multi-layer Topology:** Access, Distribution, and Core switches are configured for high-performance and redundancy.
- 🧩 **Subnetting & VLSM:** Precise subnet allocation for optimal IP utilization using the 192.168.1.0/24 block.
- 🔁 **HSRP:** Implemented across 9 VLANs for high availability and seamless failover.
- 🚪 **DHCP & NAT Overload:** Dynamic IP allocation and internet access using NAT pools for two ISPs.
- 📡 **Redundant Internet Access:** Dual ISP integration for reliability.
- 🌍 **DNS + Web Server Hosting:** Public-facing web services bound to private IPs using authoritative DNS and NAT.

---

## 🔍 Key Network Topology Overview

📎 [View our full interactive network diagram on Miro](https://miro.com/welcomeonboard/NWIybk5ON002c3dQQmU4MEZJeC9Ta2c2aVBnQ3c5Rmc0UURoelRpZURHN0x4OHhTd3RNYWpDbVQ4UTRTQm9ldzNydW5QNHNMeXFMQW9EWkFicGJDSHczcmlBaWg3ekZuTnZVb1kyOU01ai9CY3VPZlBYU2VCMjlRUjZYc2RkQVdhWWluRVAxeXRuUUgwWDl3Mk1qRGVRPT0hdjE%3D?share_link_id=879219975505)

🖼️ The diagram includes:
- 4 access switches (SW1–SW4)
- 2 distribution switches (DSW1 & DSW2)
- 2 core routers (R1 & R2)
- All VLANs, subnets, routing protocols, NAT configuration, and services

---

## 💡 Reflections on AI Assistance

We leveraged **Generative AI tools like ChatGPT** throughout the project for:
- 🔧 Troubleshooting network configs (e.g., DNS caching issues, NAT)
- 🧾 Clarifying technical terms
- ✍️ Enhancing report clarity and professional tone

Despite its benefits, we also observed some drawbacks:
- Overly verbose answers at times
- Occasional inconsistent config recommendations
- Limited understanding of exact Cisco Packet Tracer environments

---

## ⚠️ Disclaimers

> 🛑 **This is a school project** developed as part of the **ICT1013 Computer Networks module** at [Your School Name].

> 🧰 **Cisco Packet Tracer** is a proprietary simulation tool by Cisco and is used here for **educational purposes only**. All configurations and simulations are fictional.

> 🧩 **Miro** is a third-party collaborative diagramming platform used to visualize our network. The visual topology is a **conceptual representation** and not affiliated with any real-world enterprise.

---

## 👥 Contributors

- **Adil Amr Bin Qamaruzzaman**
- **Muhd Wafiyuddin Bin Abdul Rahman**
- **Nurul Aida Binte Zakaria**
- **Muhammad Nafis Bin Mohamed Idris**
- **Muhammad Saad Bin Hadi**

---

## 📄 License

This repository is provided for educational reference only and is **not intended for commercial use**.

---

🛰️ _"Building networks for a better-connected future."_
