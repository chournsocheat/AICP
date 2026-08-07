# Network Plan

## Overview

The AICP platform uses a segmented network architecture to isolate infrastructure, services, and management traffic.

---

## Network Layout

Internet
    │
Router / Firewall
    │
Proxmox Host
    │
──────────────────────────────────
│            │             │
VM Network   Docker        Storage
│            │             │
AI           Database      Backup
Automation   Monitoring    Media

---

## Planned IP Addressing

| Network | Purpose |
|---------|----------|
| Management | Proxmox Management |
| VM Network | Virtual Machines |
| Docker Network | Docker Containers |
| Storage Network | Backup & Storage |
| VPN Network | Remote Access |

---

## Remote Access

- WireGuard VPN
- Cloudflare Tunnel (Optional)

---

## Security Goals

- Separate management traffic
- Isolate databases
- Protect AI services
- Restrict public access