# Screenshots

| File | Shows |
|---|---|
| `01-topology.png` | Full logical topology: HQ and Branch sites, VLAN subnets, OSPF WAN link |
| `02-staff-web-allowed.png` | Staff PC loads `http://intranet.lab` (web + DNS permitted by STAFF_IN) |
| `03-acl-hit-counts.png` | `show access-lists STAFF_IN` on R1 with match counters from the tests |
| `04-ospf-neighbors.png` | R2: OSPF neighbor 1.1.1.1 FULL, HQ subnets learned via OSPF |
| `05-guest-blocked.png` | Simulation mode: a Guest packet dropped at R1 by GUEST_IN |
| `06-staff-ping-blocked.png` | Staff PC ping to the IT server fails (ICMP denied by STAFF_IN) |
