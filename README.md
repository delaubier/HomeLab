# HomeLab & Private Cloud Infrastructure

🌐 **Language / Langue** : **English 🇬🇧** • [Français 🇫🇷](README.fr.md)

This repository documents the architecture, configuration, and deployment of my self-hosting infrastructure (HomeLab). The goal of this project is to maintain a sovereign, secure, and automated private cloud, while serving as an experimental environment for my Data Science and AI workloads.

---

## Architecture & Tech Stack

The infrastructure is hosted *on-premise* on a refurbished machine optimized for power efficiency, offering redundant storage and local compute capacity. It is managed using **TrueNAS Scale**, a Linux-based operating system with integrated containerization.

- **OS / Hypervisor:** TrueNAS Scale
- **Reverse Proxy & Ingress:** Nginx Proxy Manager (Routing, centralized management, and SSL certificate automation).
- **Network & DNS:** AdGuard Home (DNS filtering and local network security).

---

## Deployed Services (Containers)

### Artificial Intelligence (Self-Hosted)
- **Ollama & Open-WebUI:** Local execution and interaction with Large Language Models (LLMs) on dedicated hardware, ensuring total data sovereignty and privacy.

### Cloud & Data Management
- **Nextcloud:** Secure file hosting, synchronization, and private cloud solution.
- **Immich:** Intelligent photo library and high-performance automated backup solution.

### Media Streaming & Automation
- **Jellyfin:** Open-source media streaming server.
- **Arr Ecosystem & Download Pipeline:** Interconnected and automated pipeline for media management, acquisition, and organization (Sonarr, Radarr, Readarr, Bazarr, Prowlarr, qBittorrent, Flaresolverr).
