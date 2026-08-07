| VM   | Hostname   | Purpose                                   | vCPU | RAM   | Storage |
| ---- | ---------- | ----------------------------------------- | ---- | ----- | ------- |
| VM01 | docker     | Docker Platform                           | 4    | 8 GB  | 100 GB  |
| VM02 | ai         | AI Services (Ollama, Open WebUI, Whisper) | 8    | 32 GB | 500 GB  |
| VM03 | automation | n8n, Flowise, Langflow                    | 4    | 8 GB  | 100 GB  |
| VM04 | database   | PostgreSQL, Redis, Qdrant                 | 4    | 16 GB | 200 GB  |
| VM05 | windows    | Windows Server                            | 4    | 8 GB  | 120 GB  |
| VM06 | media      | Jellyfin                                  | 4    | 8 GB  | 200 GB  |
| VM07 | monitor    | Grafana, Prometheus, Loki                 | 2    | 4 GB  | 80 GB   |
| VM08 | backup     | Backup & Restore                          | 2    | 4 GB  | 200 GB  |
