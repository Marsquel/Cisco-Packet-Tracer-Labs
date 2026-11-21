# Lab 002 — DHCP Office Network

## Overview
Upgraded the Summit Solutions office network to assign workstation IP settings automatically through DHCP instead of configuring each PC manually.

## What I Did
- Configured a Cisco 2911 router as the DHCP server.
- Created the `OFFICE-LAN` pool with an assignment range of `192.168.10.100–192.168.10.150`.
- Configured gateway and DNS settings for DHCP clients.
- Verified that all five PCs received unique addresses and could communicate.
- Tested DHCP release/renew and checked router leases using `show ip dhcp binding`.

## Skills Demonstrated
DHCP · Address pools and exclusions · Cisco IOS · IP configuration · Network verification

## Evidence
- [Network topology](topology.png)
- [DHCP client verification](dhcp-verification.png)
- [DHCP bindings](dhcp-bindings.png)
- [Ping tests](ping-tests.png)
- `Lab-002-DHCP-Office-Network.pkt` — Packet Tracer project
