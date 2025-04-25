# 🏥 Hospital Network System

## 🚀 Project Overview
The **Hospital Network System** is a secure and efficient network infrastructure designed for hospital management. It implements VLAN segmentation, static routing, and access control to ensure secure communication between departments like Radiology, Emergency, and Administration while maintaining traffic isolation.

---

## 📌 Core Features

### 🌉 **Network Segmentation**
- 8 dedicated VLANs for departments (Radiology, IT, HR, etc.)
- Traffic isolation for security and performance optimization

### 🔒 **Secure Communication**
- Access Control Lists (ACLs) to restrict unauthorized access
- Inter-VLAN routing for controlled departmental communication

### 🛡️ **Reliable Connectivity**
- Static routing configuration between floors
- 0% packet loss verified through ping tests

### ✅ **Monitoring & Validation**
- Wireshark analysis for packet flow verification
- Comprehensive connectivity testing

---

## 🏗️ System Architecture

### 💻 **Network Topology**
🔸 **3-Floor Structure**:
  🔹 Ground Floor: Reception, Emergency, Pharmacy
  🔹 Administrative Floor: Billing, HR, Administration
  🔹 Medical Floor: IT, Radiology
🔸 **Central Router** for inter-VLAN routing

### 🔧 **Technical Implementation**
| **Component**       | **Configuration**                     |
|---------------------|--------------------------------------|
| VLAN Segmentation   | 8 VLANs (10-80) with dedicated subnets |
| IP Addressing       | 192.168.1.0/24 to 192.168.8.0/24     |
| Routing             | Static routes between subnets        |
| Security            | ACLs and VLAN isolation              |

### 🛠 **Tech Stack & Tools**
| **Category**       | **Technologies Used**                |
|--------------------|--------------------------------------|
| Network Design     | VLANs, Subnetting, Static Routing    |
| Security           | ACLs                                 |
| Testing Tools      | Cisco Packet Tracer, Wireshark       |
| Protocols          | IPv4, ICMP                           |

---

## 🔥 Challenges Overcome
- **Secure Segmentation:** Implemented VLAN isolation while maintaining necessary inter-department communication
- **Routing Optimization:** Configured static routes for efficient packet flow between floors
- **Validation:** Conducted thorough testing using ping and Wireshark analysis

---

## 📈 Future Enhancements
- Implement dynamic routing protocols (OSPF/EIGRP)
- Add VoIP integration for hospital communication
- Expand to wireless network for mobile devices

---

## 👥 Team Members
| **Name**            | **Role**                              |
|---------------------|--------------------------------------|
| M. Attaullah        | Network Design & VLAN Configuration  |
| M. Haris Nisar      | IP Subnetting & Security             |
| Abdul Rehman        | Routing & Testing                    |
| Muqaddas Ali        | Documentation & Validation           |

---

## 🤝 Connect With Me
[![GitHub](https://img.shields.io/badge/GitHub-000?logo=github&logoColor=white)](https://github.com/M-Attaullah) [**M-Attaullah**](https://github.com/M-Attaullah)  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-attaullah-705764333/) [**Muhammad Attaullah**](https://www.linkedin.com/in/muhammad-attaullah-705764333/)
