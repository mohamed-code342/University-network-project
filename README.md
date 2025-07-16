# 🏫 University Campus Network Design - Cisco Packet Tracer

This project is a network simulation of a university campus created using **Cisco Packet Tracer**.  
The design includes **4 buildings**: Engineering, Medicine, IT, and Administration — each with its own VLAN and subnet.

---

## 📌 Overview

- 🔄 The network uses **/26 subnetting** for IP allocation.
- 🔐 Default password for all switches and devices: `1234`
- 📁 Each VLAN contains **2 PCs**
- 🌐 VLANs are configured for: `IT`, `HR`, and `Student`
- 📡 Inter-building communication is enabled via routers and switches.

---

## 🗂️ VLAN Configuration

| VLAN     | IP Range              | Usable IPs         | Broadcast IP   | Network IP    |
|----------|------------------------|--------------------|----------------|---------------|
| IT       | 10.0.0.0/26            | 10.0.0.1 → 10.0.0.62 | 10.0.0.63      | 10.0.0.0      |
| HR       | 10.0.0.64/26           | 10.0.0.65 → 10.0.0.126 | 10.0.0.127     | 10.0.0.64     |
| Student  | 10.0.0.128/26          | 10.0.0.129 → 10.0.0.190 | 10.0.0.191     | 10.0.0.128    |

> **Note:** Telnet IPs are included in the usable range but not listed here.

---

## 🖥️ Each VLAN Includes:

- **2 PCs per VLAN**
- Proper configuration for IP address, gateway, and connectivity.

---

## 🔧 Switch Configuration

- All switches are configured with:
  - Default password: `1234`
  - Basic VLAN assignment
  - Telnet/SSH access (if needed)

---

## 📡 Routing Table

Routing between buildings is handled using routers. Each building acts as a separate network with its own subnet and routing setup.

---

## 🏢 Campus Buildings

- **Engineering**
- **Medicine**
- **IT**
- **Administration**

Each building is wired to its own switch and VLAN configuration.

---

## 📷 Project Files

- `university-network.pkt`: Main Cisco Packet Tracer file
---

## 🧰 Tools Used

- Cisco Packet Tracer
- Subnetting (/26)
- VLAN & Inter-VLAN Routing
- Basic Network Security

---

## 📬 Contact

For more information or collaboration, reach out to:

📧 **mahammadsaad74@gmail.com**  
🔗 [LinkedIn](http://www.linkedin.com/in/mahammad-saad-725825290)

---
