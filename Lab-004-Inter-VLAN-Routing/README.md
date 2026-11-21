# Lab 004 — Inter-VLAN Routing

## Overview
Extended the Summit Solutions VLAN network by implementing Router-on-a-Stick, allowing separate departments to communicate through a Cisco router.

## What I Did
- Connected a Cisco 2911 router to the existing Cisco 2960 switch.
- Configured an 802.1Q trunk on switch port `Fa0/24` for VLANs 10, 20, and 30.
- Created router subinterfaces with a gateway address for each VLAN.
- Verified that all three router subinterfaces were up and the trunk was operational.
- Successfully tested routing from Sales to HR and IT workstations.

## Skills Demonstrated
Inter-VLAN routing · Router-on-a-Stick · 802.1Q trunking · Cisco subinterfaces · Layer 2/Layer 3 integration

## Evidence
- [Network topology](topology.png)
- [Router interfaces](router-interfaces.png)
- [Trunk verification](trunk-verification.png)
- [Inter-VLAN ping tests](inter-vlan-pings.png)
- `Lab-004-Inter-VLAN-Routing.pkt` — Packet Tracer project
