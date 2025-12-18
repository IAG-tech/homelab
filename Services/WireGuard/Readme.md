# WireGuard v0.1 - Secure Remote Access

## 🎯 Purpose
Provide secure remote access to internal systems in a controlled environment. 
## ⚙️ Current Setup
- WireGuard running on Raspberry Pi 5
- VPN subnet: 10.10.10.0/24
- Routed access from VPN clients to  internal LAN (192.168.x.x/24)
## 💻 Topology 
Client ➡️ WireGuard (wg0) ➡️ LAN

The Raspberry Pi currently acts as a temporary gateway.
## ✅ Verification
- VPN interface reachability.
- SSH access verified via local network and VPN.
## ✏️ Design Decisions
- WireGuard selected for simplicity, speed and low attack surface.
- Temporary deployment on Raspberry Pi before firewall migration.
## ⚠️ Current Limitations
- VPN endpoint located inside the LAN.
- Public access and policies will be enforced at firewall level.
## 🔜 Next Steps
- Move VPN termination to perimeter firewall.
- Enable secure remote access from external networks.
- Support site-to-site VPN connectivity between locations.
- Apply access control policies for remote connections.
- Separate operational and user access paths.
- Audit remote access.
