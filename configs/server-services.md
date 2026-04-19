# Server Services

## Internal DHCP server

The internal server provides DHCP for the client VLANs.

Planned pools:

- HR Pool: 192.168.10.0/24, gateway 192.168.10.1
- IT Pool: 192.168.20.0/24, gateway 192.168.20.1
- Sales Pool: 192.168.30.0/24, gateway 192.168.30.1
- WiFi Pool: 192.168.40.0/24, gateway 192.168.40.1
- Guest Pool: 192.168.50.0/24, gateway 192.168.50.1

## ISP-side server

- IP: 200.2.2.10
- Gateway: 200.2.2.1
- HTTP enabled
- DNS enabled
- DNS record example: jorgetestsite.com -> 200.2.2.10
