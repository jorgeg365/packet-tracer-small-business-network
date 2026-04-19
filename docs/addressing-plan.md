# Addressing Plan

## VLANs and subnets

| VLAN | Name | Subnet | Gateway |
| --- | --- | --- | --- |
| 10 | HR | 192.168.10.0/24 | 192.168.10.1 |
| 20 | IT | 192.168.20.0/24 | 192.168.20.1 |
| 30 | Sales | 192.168.30.0/24 | 192.168.30.1 |
| 40 | Employee WiFi | 192.168.40.0/24 | 192.168.40.1 |
| 50 | Guest WiFi | 192.168.50.0/24 | 192.168.50.1 |

## Server addresses

| Device | IP | Purpose |
| --- | --- | --- |
| Internal server | 192.168.10.2 | DHCP and internal services |
| ISP router inside link | 200.1.1.1 | Simulated WAN/ISP gateway |
| Main router outside link | 200.1.1.2 | NAT outside address |
| ISP-side web server | 200.2.2.10 | Public HTTP server |
| ISP router server-side link | 200.2.2.1 | Gateway for ISP server subnet |
