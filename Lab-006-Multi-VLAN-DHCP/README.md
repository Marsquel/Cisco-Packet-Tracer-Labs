\# Lab 006 — Multi-VLAN DHCP



\## Overview

Implemented centralized DHCP services across three VLANs in a simulated office network, eliminating the need for manual workstation IP configuration.



\## Configuration

\- Configured separate DHCP pools for Sales, HR, and IT.

\- Established DHCP address ranges and excluded reserved addresses.

\- Configured automatic assignment of IP addresses, subnet masks, default gateways, and DNS servers.

\- Maintained inter-VLAN routing using router-on-a-stick.



\## Verification

\- Confirmed all nine workstations received DHCP addresses from their respective VLANs.

\- Verified DHCP bindings on the router.

\- Successfully tested connectivity between Sales, HR, and IT networks.

