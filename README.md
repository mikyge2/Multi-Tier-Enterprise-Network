# Multi-Tier Enterprise Network

A multi-tiered enterprise network simulation implemented using Cisco Packet Tracer. This project showcases a scalable partial mesh topology across multiple sites with full network functionality using VLANs, OSPF, NAT, ACL, DHCP, DNS, and more.

---

## 🗺️ Network Topology: Partial Mesh

The network is designed using a **partial mesh topology** to balance redundancy, scalability, and cost-effectiveness. Direct connections between essential sites improve communication efficiency without the complexity of a full mesh.

### 🌐 Connected Sites:

- **Main Site** ↔ Regional Office, Manufacturing Facility, Distribution Center  
- **Regional Office** ↔ Main Site, Distribution Center, Remote Site  
- **Manufacturing Facility** ↔ Main Site, Distribution Center  
- **Distribution Center** ↔ Main Site, Regional Office, Remote Site  
- **Remote Site** ↔ Regional Office, Distribution Center  

This design allows robust, efficient communication between critical operational nodes while remaining adaptable for future scaling.

---

## 🏷️ Naming Conventions

| Device Type          | Format Example                     |
|----------------------|-------------------------------------|
| Router               | `Site+RouterID`                     |
| Multi-Layer Switch   | `Site+MLSwitchID`                   |
| Access Switch        | `Department+SwitchID`              |
| PC                   | `Department+Site+PCID`             |
| Laptop               | `Department+Site+LaptopID`         |
| Printer              | `Department+Site+PrinterID`        |
| Access Point         | `Department+Site+AP`               |
| SSID                 | `Department+Site+AP`               |
| WiFi Password        | `AP-cs461`                         |

---

## 🛠️ Technologies Implemented

1. **VLAN** – Logical separation of departments.
2. **Inter-VLAN Routing** – Communication between different VLANs.
3. **Subnetting** – Logical subdivision of IP networks.
4. **OSPF Routing** – Dynamic routing between routers.
5. **DHCP** – Automated IP assignment to end devices.
6. **DNS** – Resolving domain names to IP addresses.
7. **HTTPS** – Secure web access to internal services.
8. **NAT (PAT)** – Public IP translation for external access.
9. **ACL** – Security rules for traffic control and NAT permissions.

---

## 📁 Project Files

| File Name | Description |
|----------|-------------|
| `FullyDoneNoNATandACL.pkt` | Final working version without NAT and ACL implemented |
| `NATandACLonMainSiteRouter.pkt` | NAT & ACL configured on the Main Site router |
| `Multi Tier Enterprise Network Documentation.pdf` | Full project documentation and topology explanation |
| `README.md` | Project overview and documentation (this file) |


---

## 🚀 How to Open the Project

1. Download **Cisco Packet Tracer** from [Cisco NetAcad](https://www.netacad.com/)
2. Clone or download this repository.
3. Open `.pkt` files inside Packet Tracer.
4. Use simulation mode to test OSPF routing, NAT, ACL, and device connectivity.

---

## 👨‍💻 Author

**GitHub:** [@mikyge2](https://github.com/mikyge2)

For educational, research, and lab simulation purposes.

---

## 📜 License

This project is open-source and free to use for learning and demonstration purposes.

