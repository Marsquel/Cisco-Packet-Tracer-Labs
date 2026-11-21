\# Lab 005 — Network Access Control Lists (ACLs)



\## Overview

Implemented an extended IPv4 ACL to control communication between departments in a simulated office network.



\## Configuration

\- Configured subnet-based filtering using wildcard masks.

\- Restricted Sales (VLAN 10) from accessing HR (VLAN 20).

\- Permitted ICMP echo replies to allow HR-initiated pings.

\- Applied the ACL inbound on the Sales router subinterface.

\- Permitted all other traffic.



\## Verification

\- \*\*Sales → HR:\*\* Blocked.

\- \*\*HR → Sales:\*\* Successful.

\- Confirmed ACL rules were applied in the correct order.

