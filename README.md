# OSPF-Multi-Area-Routing-Cisco-Packet-Tracer
Cisco Packet Tracer lab demonstrating OSPF Multi-Area routing with Area 0 and Area 1, connecting two end-user networks through three routers.


# 🌐 OSPF Multi-Area Routing
### Cisco Packet Tracer Networking Lab

<p align="center">
  <b>Dynamic Routing • OSPF Area 0 • OSPF Area 1 • Inter-Area Routing • Network Troubleshooting</b>
</p>

---

## 📌 Project Overview

This project demonstrates a **Multi-Area OSPF network** built in Cisco Packet Tracer.

The topology uses **three routers** to connect two end-user networks. The routing domain is divided into **OSPF Area 0** and **OSPF Area 1**, providing practical experience with multi-area dynamic routing and inter-area communication.

The project focuses on understanding how routers exchange routing information, establish OSPF neighbor relationships, learn remote networks, and provide end-to-end connectivity between separate LANs.

---

## 🖧 Network Topology

```text
                    OSPF AREA 0                 OSPF AREA 1

 PC1
  │
  │
 SW1
  │
  │
 R1 ═══════════ R2 ═══════════ R3
                 │               │
                 │               │
             Area 0          Area 1
                                 │
                                SW2
                                 │
                                PC2
