# Lab 003 — Department VLANs

## Overview
Segmented the Summit Solutions office network into separate Sales, HR, and IT departments using VLANs on a Cisco 2960 switch.

## What I Did
- Created VLAN 10 (Sales), VLAN 20 (HR), and VLAN 30 (IT).
- Assigned three workstations and dedicated switch access ports to each VLAN.
- Configured static IP addresses in separate departmental subnets.
- Confirmed that PCs within each VLAN could communicate.
- Verified that traffic could not cross between VLANs without routing.

## Skills Demonstrated
VLANs · Layer 2 switching · Access ports · Network segmentation · ICMP testing

## Evidence
- [Network topology](topology.png)
- [VLAN configuration](vlan-configuration.png)
- [Same-VLAN connectivity](same-vlan-ping.png)
- [Inter-VLAN isolation](inter-vlan-test.png)
- `Lab-003-Department-VLANs.pkt` — Packet Tracer project
