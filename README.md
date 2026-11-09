# Palo Alto Site-to-Site IPsec VPN

## Project Overview

This project demonstrates the implementation of a Site-to-Site IPsec VPN using Palo Alto Networks firewalls in a virtual lab environment.

The objective is to establish secure and encrypted communication between two geographically separated networks representing Saudi Arabia and London.

## Tools & Technologies

- Palo Alto Networks Firewall (PAN-OS)
- GNS3
- VMware Workstation
- IPsec VPN
- IKEv2
- Static Routing
- Firewall Security Policies

## Network Architecture

The lab consists of two virtual Palo Alto firewalls, a WAN transit router, and end-user devices at both sites.

Each firewall uses dedicated WAN, LAN, and VPN tunnel interfaces to support communication between the networks.

## Implementation

The project covers:

1. Network topology design using GNS3.
2. Palo Alto firewall interface and security zone configuration.
3. IKE Phase 1 configuration.
4. IPsec Phase 2 configuration.
5. Site-to-Site VPN tunnel implementation.
6. Static routing configuration.
7. Firewall security policy configuration.
8. Connectivity testing and troubleshooting.

## Security Configuration

**IKE Phase 1**
- Encryption: AES-256-CBC
- Authentication: SHA-256
- DH Group: 14
- Lifetime: 8 hours

**IPsec Phase 2**
- Protocol: ESP
- Encryption: AES-256-CBC
- Integrity: SHA-256
- PFS Group: 14
- Lifetime: 1 hour

## Testing & Validation

Connectivity tests were performed between the two simulated networks to validate traffic forwarding and the VPN configuration.

## Documentation

The project includes technical documentation covering the network architecture, configuration steps, security policies, and testing procedures.

## Project Type

Cybersecurity | Network Security | Firewall Configuration | VPN Implementation

*Developed as part of a collaborative cybersecurity training project.*
