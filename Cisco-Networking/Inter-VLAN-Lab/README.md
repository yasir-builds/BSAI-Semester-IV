# Inter-VLAN Routing Lab 🌐

This lab demonstrates communication between two separate VLANs using a **3560-24PS Multilayer Switch**. 

## 📍 Network Topology
Below is the logical design of the network, showing the separation of VLAN 1 (Blue) and VLAN 2 (Red).

![Network Topology](Network%20Topology.jpg)

## ⚙️ Configuration Details
* **VLAN 1 (Blue):** Subnet `192.168.10.0/24`
* **VLAN 2 (Red):** Subnet `192.168.20.0/24`
* **Routing:** Configured Switch Virtual Interfaces (SVI) to allow traffic between different subnets.

## 📈 Connectivity Results
The following screenshot confirms a successful ping from **PC0 (VLAN 1)** to **192.168.20.2 (VLAN 2)**, proving that the Multilayer Switch is correctly routing the traffic.

![Ping Results](Ping%20Results.jpg)

---
*Note: Open the `.pkt` file in Cisco Packet Tracer to view the full CLI configuration.*
