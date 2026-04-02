# Enterprise-Network-Troubleshooting-Lab-CCNA-Level-
Designed and Implemented a mult-router enterprise network in Cisco Packet Tracer, incorporating VLAN segmentation, inter-VLAN routing, OSPF, DHCP, ACLs and NAT. Simulated real-world network failures and performed structured troubleshooting to restore connectivity across internal networks and external internet access.

# Network Topology
Description:

-R1: Router-on-a-stick (VLAN 10 and VLAN 20)
-R2: Core routing (OSPF transit)
-R3: Edge router (Server network + NAT + ISP)

-VLAN 10: 192.168.10.0/24 (PC1)
-VLAN 20: 192.168.20.0/24 (PC2)
-VLAN 30: 192.168.20.0/24 (PC3)

-R1 ⇔ R2: 10.0.12.0/24
-R2 ⇔ R3: 10.0.23.0/24
-R3 ⇔ ISP: 200.0.0.0/30
-ISP ⇔ Public Server: 8.8.8.0/24


