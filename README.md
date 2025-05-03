
# Zeronx Small Business Network Project

## 📅 Date
May 5, 2025  
**Created by:** Md. Istiuk Ahmed Mitul  
**Course Title:** Networking Fundamentals

---

## 🏢 Company Overview

**Company Name:** Zeronx  
**Business Type:** Technology consulting firm specializing in IT solutions for local businesses.

**Services Offered:**
- Network installation & configuration  
- IT troubleshooting  
- Managed services  

**Team Size:** 6 full-time employees (consultants, technicians, and administrative staff)

---

## 📡 Business Needs

- Secure and reliable internal LAN for daily operations  
- Centralized server for internal services (DNS, DHCP) and public web hosting  
- External access to company website via Internet  
- Scalable infrastructure to support future growth  

---

## 🖥️ Network Design Overview

**Network Components:**
- 2 Routers (Internal + Edge)
- 2 Switches
- 4 PCs (Employee workstations)
- 1 Server (Web, DNS, DHCP)
- 1 External client (for testing Internet access)

---

## 🔧 Internal Network Setup

- **Devices:** PC0 to PC3, Central Server  
- **Services:** DHCP, DNS, HTTP  
- **IP Addressing:** Private range (10.10.10.x)  
- **Topology:** LAN segments connected via switch and internal router  

---

## 🌐 Web Server & Public Access

- **Web Server:** Hosts website at [http://www.company.com](http://www.company.com)  
- **DNS:** Resolves domain name to server’s public IP  
- **External Access:** External client successfully browses the website  

---

## 🌍 Internet & NAT Configuration

- **NAT Router:** Translates internal private IPs to a public IP  
- **External Testing:** External client can ping and browse the internal web server using DNS  

---

## 🛠️ Services Implemented

- **DHCP:** Automatically assigns IPs to internal devices  
- **DNS:** Resolves domain names internally and externally  
- **NAT:** Enables internal devices to access the Internet securely  

---

## ✅ Design Justification

- **Wired LAN:** More reliable and secure than wireless alternatives  
- **Two Routers:** Separates LAN from WAN for better control and security  
- **Central Server:** Combines DNS and Web services, simplifying management  
- **Scalability:** Supports expansion with minimal changes  

---

## 📌 Project Summary

- All internal devices can communicate and are pingable  
- DNS successfully resolves `www.company.com`  
- Website is accessible both internally and from the Internet  

---

## 📁 Repository Contents

- 📝 `README.md` – Project summary and explanation  
- 📸 `network_design.png` – Network topology diagram 
- 📊 `project presentation.pptx` – Original presentation (attached in this repo)
- 📸 'zeronx_network_setup.pkt' - The working design made using CISCO Packet Tracer

---

## 💡 Future Improvements

- Add wireless access points for mobile access  
- Implement firewall policies for better security  
- Integrate monitoring tools for network performance

---

## 📬 Contact

For questions or collaboration, please contact:  
📧 istiukahmedmitul@gmail.com

