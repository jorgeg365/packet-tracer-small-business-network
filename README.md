# Packet Tracer Small Business Network

This repository documents a Packet Tracer networking project for a small business with segmented departments, wireless access, DHCP, NAT, DNS, and basic ACL-based security.

## What is included

- Router-on-a-stick inter-VLAN routing
- Department VLANs for HR, IT, Sales, Employee WiFi, and Guest WiFi
- DHCP service for all client VLANs
- ACL policy to block HR from IT while allowing approved traffic
- NAT to a simulated ISP network
- External DNS and web server access
- Guest WiFi isolation

## Current lab design

- Main router: inter-VLAN routing and NAT
- Core switch: VLANs and trunking
- Internal server: DHCP for client VLANs
- AP for employee WiFi on VLAN 40
- AP for guest WiFi on VLAN 50
- ISP router: public-side routing
- ISP server: DNS and web hosting

## Folder structure

- `packet-tracer/` Packet Tracer project files
- `configs/` saved configuration snippets
- `docs/` design notes and addressing tables
- `screenshots/` screenshots used for documentation

## Suggested next steps

1. Add the final `.pkt` file to `packet-tracer/`
2. Add your screenshots to `screenshots/`
3. Export any command outputs you want to keep in `configs/`

## Summary

The project demonstrates a realistic small business network with separate departments, wireless segmentation, internet simulation, and name-based web access.
