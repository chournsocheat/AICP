# Storage Plan

## Overview

Storage is divided into separate areas to improve performance, simplify backup, and reduce the impact of failures.

---

## Storage Layout

| Storage | Purpose |
|---------|---------|
| Proxmox OS | Proxmox VE operating system |
| VM Storage | Virtual machine disks |
| Docker Data | Docker volumes and containers |
| AI Models | Ollama and Whisper models |
| Database | PostgreSQL, Redis, Qdrant |
| Media | Jellyfin media library |
| Backup | VM backups and snapshots |

---

## Backup Strategy

- Daily database backup
- Weekly VM backup
- Monthly full backup
- Test restore procedure regularly

---

## Future Expansion

- Additional NVMe SSD
- NAS integration
- Object Storage (MinIO)
- Off-site Backup