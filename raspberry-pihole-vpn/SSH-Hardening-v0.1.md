# SSH HARDENING

⚠️ Work in progress 

This is the v0.1 version, ssh key authentication will be added soon. More improvements in the next versions.

----

## 💡 What

Hardening focuses on strengthening the security of enterprise, industrial and home networks exposed to the internent. In this document, I apply that idea to my personal homelab, specifically improving the security of the SSH service I use to manage my Raspberry Pi 2B.

## 🎯 Why

SSH is the main entry point for remote administration. Securing it properly helps prevent unauthorized access and prepares the system for further layers of protection such as VPN, firewall rules, and intrusion prevention.

----

## Hardening Progress

| Security Area | Description | Status | Documentation |
|----------------|--------------|---------|----------------|
| SSH Key Authentication | Add login with SSH keys | ✅ Implemented (v0.1) | **🔗[SSH Key Setup](SSH-Keys.md)** |
| VPN Access | Tunnel SSH through a secure VPN layer | ⏳ Planned (v0.2) | **Coming soon**  |
| Firewall Rules | Restrict SSH access to trusted IPs only | ⏳ Planned (v0.3) | **Coming soon**  |
| Disable Password Login | Enforce key-only authentication | ⏳ Planned (v0.4) | **Coming soon**  |
| Fail2Ban | Block repeated failed login attempts | ⏳ Planned (v0.5) | **Coming soon** |
| Bastion Host | Centralize SSH access through a hardened jump host | ⏳ Planned (v0.6) | **Coming soon** |



-----









