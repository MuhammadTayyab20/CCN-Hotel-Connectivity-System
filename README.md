# CCN — Hotel Connectivity System 🏨

A secure, scalable multi-floor hotel network designed and simulated in **Cisco Packet Tracer**. The network segments traffic by floor/department using VLANs, routes between them with OSPF, automates addressing with DHCP, and hardens access with SSH and port security.

---

## 🎯 Project Goal

Design an enterprise-grade network for a multi-floor hotel where each floor (and service area such as reception, guest rooms, admin, and management) is isolated for security and performance, while still allowing controlled communication across the building.

---

## 🧩 Key Features

- **VLANs** — separate broadcast domains per floor/department for isolation and easier management
- **OSPF routing** — dynamic routing between VLANs and network segments
- **DHCP** — automatic IP assignment to client devices
- **SSH** — secure remote management of switches and routers (no plain Telnet)
- **Port security** — restricts which devices can connect to switch ports, preventing unauthorized access

---

## 🛠️ Tools Used

- **Cisco Packet Tracer** 
---

## 🗺️ Topology

> Add a screenshot of your Packet Tracer topology here, plus a short note on the IP/VLAN scheme.
>
> Example:
> | VLAN | Purpose | Subnet |
> |------|---------|--------|
> | 10 | Reception | 192.168.10.0/24 |
> | 20 | Guest Rooms | 192.168.20.0/24 |
> | 30 | Admin | 192.168.30.0/24 |

---

## ▶️ How to Open

1. Open the `.pkt` file in **Cisco Packet Tracer**.
2. Explore the device configurations (CLI on each router/switch).
3. Use **Simulation mode** to trace packets between VLANs.

---

## 📌 Possible Improvements

- [ ] Add a firewall / ASA for internet edge security
- [ ] Add a guest Wi-Fi VLAN with captive portal
- [ ] Add redundancy (HSRP / EtherChannel)
