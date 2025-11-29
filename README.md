# Basic Router Configuration & Remote Management Lab

This lab demonstrates how to configure a Cisco router from scratch and enable remote management using SSH. The project focuses on secure access, interface configuration, routing, and device hardening.

## Topology

- 1 Router (R1)
- 1 Switch (S1)
- 2 PCs (PC1 for management, PC2 for testing)
- Two networks:
  - 192.168.10.0/24 (Management Network)
  - 10.10.10.0/24 (Remote Network)

## Features Configured

- Hostname and basic settings
- IPv4 interface configuration
- Console and VTY security
- SSH remote login
- Static routing
- Password encryption
- MOTD login banner

## Key Commands Used

- `crypto key generate rsa`
- `ip ssh version 2`
- `line vty 0 15`
- `interface Gig0/0/0`
- `ip route 0.0.0.0 0.0.0.0 ...`

## Results

- SSH access successfully established from PC1 to R1.
- Routing works between both LAN segments.
- All management lines protected with encrypted passwords.

## Skills Demonstrated

- Cisco IOS CLI configuration
- Remote management + SSH security
- Routing configuration
- Device hardening
