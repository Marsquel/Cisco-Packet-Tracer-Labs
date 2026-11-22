\# Lab 007 — Network Address Translation (NAT \& PAT)



\## Overview

Configured Network Address Translation (NAT) with Port Address Translation (PAT) to provide external network connectivity for three internal VLANs using a single external IP address.



\## Configuration

\- Added an ISP router and external web server to simulate internet connectivity.

\- Configured static default routing toward the ISP.

\- Designated NAT inside and outside interfaces.

\- Created an ACL to identify internal networks for translation.

\- Implemented PAT using NAT overload.



\## Verification

\- Successfully established external connectivity from Sales, HR, and IT.

\- Verified private IP addresses were translated to the router's external IP address.

\- Confirmed NAT translations and statistics using Cisco IOS commands.

