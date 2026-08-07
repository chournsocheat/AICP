# AICP Architecture

## Overview

AICP (AI Cloud Platform) is a self-hosted private infrastructure designed to host AI services, automation workflows, development environments, databases, media services, and enterprise applications on a single platform.

The platform is built on Proxmox VE and follows a modular architecture so that each service can be managed, backed up, and scaled independently.

---

## Architecture Layers

### Layer 1 – Hardware

Physical server resources:

- CPU
- Memory
- GPU
- Storage
- Network

---

### Layer 2 – Hypervisor

- Proxmox VE

Responsibilities:

- Virtualization
- Storage Management
- Snapshots
- Backup
- High Availability (Future)

---

### Layer 3 – Virtual Machines

Planned virtual machines:

- Docker Platform
- AI Platform
- AI Automation
- Database
- Windows Server
- Monitoring
- Media Server
- Backup Server

---

### Layer 4 – Container Platform

Docker and Docker Compose will host most application services.

Examples:

- Portainer
- Ollama
- Open WebUI
- n8n
- PostgreSQL
- Redis
- Jellyfin

---

### Layer 5 – AI Services

Core AI components:

- LLM Inference
- Speech Recognition
- Knowledge Base
- AI Automation
- AI Agents

---

### Layer 6 – User Access

Users access services through:

- Web Browser
- Mobile Device
- API
- VPN
- Cloudflare Tunnel

---

## Design Principles

- Modular
- Secure
- Scalable
- Easy Backup
- Easy Restore
- Infrastructure as Code
- AI First

---

## Future Expansion

- Kubernetes Cluster
- Multi-node Proxmox Cluster
- GPU Pool
- Enterprise SSO
- Multi-site Backup