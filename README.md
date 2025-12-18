# 🏠 Homelab

This repository documents my hands-on homelab focused on networking, Linux, system administration and security operations.

The lab is designed to simulate real world NOC/SOC scenarios: secure remote access, DNS security, monitoring, logging and incident-oriented tooling.

## 🎯Goals

- Build a solid base in networks (routing, VLANs,  DNS, VPNs).
- Improve security/hardening practices.
- Strengthen Linux system administration skills.
- Learn by doing instead of only reading or lab simulating.

## Lab Architecture
The homelab is split into two main environments:
  - **Core Infrastructure (Raspberry Pi 2B - Village)**
    -    Always-on services
    -    DNS filtering and privacy
    -    Low resource, high availability mindset
  - **Security & Operations Lab (Raspberry Pi 5 - Zaragoza)**
    -    Secure remote access (VPN)
    -    Monitoring and SOC-oriented tooling
    -    Future firewall integration

## Current Progress and Roadmap
### Core Infraestructure (Raspberry Pi 2B)
- ✅ SSH access with ED25519 keys 
- ✅ Basic Pi-Hole setup 
- ⌛ Pi-hole documentation (In progress)
- ⌛ Unbound (private recursive DNS)
### Secure Access & Networking (Raspberry Pi 5)
- ✅ WireGuard VPN (local access)
- ⌛ WireGuard remote access (public endpoint/ firewall)
- ⌛ Site-to-site Wireguard tunnel
### Security Operations / Mini SOC (Raspberry Pi 5)
- ⌛ Centralized logging
- ⌛ Basic onitoring and alerting
- ⌛ Traffic inspection and anomaly detection
- ⌛ Incident style documentation
### Infraestructure Evolution
- ⌛ Firewall (OPNsense)
- ⌛ Migration of VPN endpoit to firewall

This roadmap evolves as the lab grows and new experiments appear.

## 🧠 Philosophy

 *Build, break, learn and repeat until mastery.*
 
## 💻 Devices and software

- **Raspberry Pi 2B:**
  - Raspberry Pi OS Lite
  - SSH with ED25519 keys
  - Pi- hole
 
- **Raspberry Pi 5:**
  - Raspberry Pi OS Lite
  - SSH with ED25519 keys
  - WireGuard server
    
*If you´re into networks, self-hosting and learning by doing - welcome!*





