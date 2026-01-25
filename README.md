# 📶 Project: Campus Wi-Fi Deployment with Seamless Roaming

## 📸 Network Topology  
<img width="1275" height="850" alt="image" src="https://github.com/user-attachments/assets/741463f7-fc47-42c9-b44e-e2e30176fe99" />



## 📘 Overview  
This project involved a **real-world enterprise campus Wi-Fi deployment** to deliver a **high-performance, reliable, and centrally managed wireless infrastructure**.  
The solution focused on **seamless roaming**, **centralized management**, and **segmented VLAN architecture** to provide uninterrupted connectivity and enhanced network visibility across all campus areas.

The deployment was executed collaboratively by the **Network Operations Center (NOC)**, **Fiber**, and **Electrical** teams under a structured rollout plan ensuring minimal downtime and full compliance with enterprise network standards.

---

## 🧑‍💻 Role & Team Structure  

**Role:** NOC Engineer  
**Team Size:** 4 Members  
- 1 × NOC Engineer *(My Role)*  
- 1 × Fiber Engineer  
- 1 × Fiber Technician  
- 1 × Electrical Technician  

**Duration:** `9th January 2024 – 12th January 2025`  
**Project Nature:** Real-world project carried out for an enterprise client with production-grade infrastructure.

---

## 🧩 Network Architecture  

### 🔹 Project Scope  
- Design and deployment of **campus-wide wireless coverage** across multiple buildings and outdoor zones.  
- Integration of **Edgecore Switches**, **Ruijie POE switch**, **Ruijie AP** and **MikroTik RouterOS** for routing, segmentation,        Interanal network connection and authentication.  
- Configuration of **management, service, and guest VLANs** for secure traffic isolation.  
- Implementation of **AAA authentication**, **SNMP monitoring**, and **Ruijie Cloud Platform** for end-user access control.  

---


---

## ⚙️ Configuration Highlights  

### 🔸 Network Design & Segmentation  
- Designed **VLAN-based segmentation** for isolating service, management, and guest traffic.  
- Configured **Static Routing** and **DHCP pools** in MikroTik RouterOS for controlled IP assignment.  
- Applied **NAT policies** for internet access and internal route advertisements.  

### 🔸 Seamless Roaming & Wireless Optimization  
- Configured **SSID broadcasting** and **roaming** across multiple APs.  
- Calibrated transmit power and channel selection to reduce interference.  
- Implemented **dual-band Wi-Fi (2.4GHz/5GHz)** balancing to ensure performance efficiency.  

### 🔸 Cloud Management & Monitoring  
- Registered all switches and APs under a **cloud controller** for real-time visibility and centralized configuration.  
- Enabled **SNMPv2** and **syslog forwarding** to the NOC monitoring dashboard for proactive alerts.  
- Configured **TACACS+ authentication** for device access security.  
- Linked **NTP servers** to synchronize logs and event timestamps across all nodes.  

---

## 🧰 NOC Team Responsibilities  

| Phase | Activities Performed |
|-------|----------------------|
| **Pre-Deployment** | Site survey, access point placement planning, and switch rack allocation. |
| **Deployment** | Configured VLANs, routing, DHCP, and NAT; integrated switches and APs into cloud management; tested wireless coverage. |
| **Post-Deployment Validation** | Verified SSID broadcast, roaming handover, authentication, and bandwidth throughput tests. |
| **Monitoring Setup** | Deployed SNMP and syslog monitoring, created alert thresholds, and integrated network devices with the NOC dashboard. |
| **Documentation & Handover** | Prepared topology diagrams, IP plan, configuration backup, and user onboarding guide for IT operations team. |
| **Support & Maintenance** | Provided remote assistance, troubleshooting for AP disconnections, and firmware updates for switches and routers. |

---

## 🧠 Technologies Used  

| Category | Technology / Protocol |
|-----------|----------------------|
| Routing Platform | MikroTik RouterOS |
| Switching Platform | Edgecore and Ruijie POE Switches |
| Wireless Platform | Cloud-Managed Access Points |
| Connectivity | VLAN, Static Routing, DHCP, NAT |
| Management | SNMP, Syslog, TACACS+, Cloud Controller |
| Monitoring | Cloud Dashboard, NOC SNMP Alerts |
| Features | Seamless Roaming, Centralized Management |

---

## 🔍 Key Outcomes  
✅ Achieved **campus-wide seamless Wi-Fi coverage** with uninterrupted roaming.  
✅ Enabled **centralized configuration and real-time cloud monitoring** for faster response and maintenance.  
✅ Improved **network reliability** through redundancy and proactive alerting.  
✅ Delivered **enhanced user experience** with consistent signal quality and load balancing.  
✅ Strengthened **security posture** via VLAN segmentation, TACACS+, and AAA authentication.  
✅ Successfully documented and handed over complete configuration and topology records to client IT operations.  

---


---

## 🧪 Validation Tests Performed  

| Test | Description | Result |
|------|--------------|--------|
| Ping Test | Verified end-to-end connectivity between APs and router | ✅ Pass |
| VLAN Isolation | Confirmed service/management traffic separation | ✅ Pass |
| Roaming Test | Tested seamless SSID handoff between APs | ✅ Pass |
| DHCP/NAT Verification | Validated IP leasing and internet access | ✅ Pass |
| Monitoring Test | SNMP and cloud controller alerts verified | ✅ Pass |

---

## 🏁 Summary  
The **Campus Wi-Fi Deployment with Seamless Roaming** project successfully delivered a **secure, scalable, and high-performance wireless infrastructure** for an enterprise client.  
Through structured planning, VLAN segmentation, and seamless roaming implementation, the network achieved full coverage and centralized visibility under NOC management.  
This deployment established a **future-ready wireless backbone** optimized for enterprise mobility and digital services.

---






