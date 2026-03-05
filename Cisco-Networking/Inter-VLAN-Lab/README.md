# Inter-VLAN Routing Lab

This lab demonstrates communication between two different VLANs using a **3560-24PS Multilayer Switch**.

## Topology
![Network Topology](topology.png)

## Configuration Details
* **VLAN 1 (Blue):** Subnet `192.168.10.0/24`
* **VLAN 2 (Red):** Subnet `192.168.20.0/24`
* **Switching:** Configured SVI (Switch Virtual Interfaces) for routing between VLANs.

## Connectivity Test
Successfully routed traffic from PC0 (VLAN 1) to PC2 (VLAN 2).
![Ping Test](ping_result.png)