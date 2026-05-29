# 🏨 CCN Hotel Connectivity System

A secure, scalable, and multi-floor hotel network infrastructure designed and simulated using Cisco Packet Tracer. The project connects multiple hotel departments across three floors using VLAN segmentation, dynamic routing, DHCP services, wireless connectivity, and enforced security policies — meeting the operational and security requirements of a modern hotel environment.

---

## 📌 Overview

The **CCN Hotel Connectivity System** is a three-floor enterprise-style networking project developed to simulate a real-world hotel communication infrastructure.

Each floor contains multiple departments connected through dedicated VLANs to ensure secure and efficient communication. The network supports:

* Dynamic IP address allocation
* Inter-floor communication through OSPF routing
* Secure remote device management via SSH
* Port security enforcement
* Wireless connectivity for mobile and wireless devices
* Inter-VLAN communication and shared resource access

The entire network was designed and tested in **Cisco Packet Tracer**.

---

# ✨ Key Features

## 🔹 VLAN Segmentation

Each department operates within its own VLAN to:

* Reduce broadcast traffic
* Improve network performance
* Enhance security and isolation

---

## 🔹 OSPF Dynamic Routing

Routers on all three floors exchange routes dynamically using **OSPF**, enabling efficient and scalable inter-floor communication.

---

## 🔹 DHCP Services

Routers function as DHCP servers and automatically assign IP addresses to all devices based on their VLAN.

---

## 🔹 SSH Remote Access

Secure remote management is configured on all routers using **SSH** for encrypted administrative access.

---

## 🔹 Port Security

The IT department switch implements **sticky MAC port security**, allowing access only to the authorized **Test-PC** device.

---

## 🔹 Wi-Fi Connectivity

Wireless access points provide connectivity for:

* Laptops
* Smartphones
* Tablets
* Wireless printers

Each wireless network is mapped to its respective VLAN.

---

## 🔹 Inter-VLAN Routing

Inter-VLAN routing allows controlled communication between departments while maintaining segmentation and security policies.

---

# 🏗️ Network Layout

| Floor     | Departments                  | Devices                       |
| --------- | ---------------------------- | ----------------------------- |
| 1st Floor | Reception, Store, Logistics  | Router, Switch, PCs, Printers |
| 2nd Floor | Finance, HR, Sales/Marketing | Router, Switch, PCs, Printers |
| 3rd Floor | Admin, IT                    | Router, Switch, PCs, Printers |

### 📡 Infrastructure Details

* Each floor contains:

  * One dedicated router
  * One switch
  * Multiple wired and wireless devices
* Routers are interconnected using **Serial DCE links**
* Unique subnets are assigned for inter-router communication

---

# 🛠️ Technologies Used

* Cisco Packet Tracer
* VLANs
* Inter-VLAN Routing
* OSPF Routing Protocol
* DHCP
* SSH
* Port Security (Sticky MAC)
* Wireless Access Points

---


## 3️⃣ Explore Configurations

Review configurations for:

* Routers
* Switches
* VLANs
* DHCP
* OSPF
* Security policies

---


# ✅ Testing & Verification

The following tests were successfully verified:

* ✔️ Devices across VLANs communicate through OSPF routing
* ✔️ DHCP correctly assigns IP addresses per VLAN
* ✔️ SSH remote login works on all routers
* ✔️ Unauthorized devices are blocked by port security
* ✔️ Wireless devices connect successfully
* ✔️ Cross-VLAN printing functions correctly

---


# 📷 Suggested Repository Additions

To make this project stand out on GitHub, consider adding:

* 📸 Network topology screenshots
* 🎥 Demo video/GIF
* 📑 Configuration files
* 📊 IP addressing table
* 🧠 VLAN/subnet design diagrams

---

# ⭐ Project Status

✅ Completed
📚 Academic Networking Project
🛡️ Focused on Secure Enterprise Network Design
