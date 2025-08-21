# 🖥️ Chrono's Homelab

> *"A powerful learning environment built on repurposed hardware."*

This is my personal homelab, built on a my first gaming PC. It serves as my primary platform for experimenting with DevOps tools, containerization, networking, and self-hosted services.

## 🔧 Hardware Specifications

| Component            | Specification                               |
|----------------------|---------------------------------------------|
| **CPU**              | AMD FX-6300 (6 Cores @ 3.5GHz)              | 
| **RAM**              | 20 GB DDR3                                  | 
| **GPU**              | NVIDIA GTX 970 4GB                          | 
| **Primary Storage**  | 12 TB Seagate IronWolf HDD                  | 
| **Boot Drive**       | 256GB Western Digital SSD                   |
| **PSU**              | Antec Atom 450W                             | 
| **Case**             | Antec GX300                                 | 
| **OS**               | Ubuntu Server 22.04 LTS (Headless)          | 

## 🌐 Network Overview

Not currently available, nuking and rebuilding the server



*   **Hostname:** `void`
*   **Local IP:** `192.168.3.133`
*   **Access:** Primarily via SSH.

## 🐳 Deployed Services

Here are the core services currently running on the lab via Docker Compose:

| Service | Description | Status | Web Interface |
| :--- | :--- | :---: | :--- |
| **Portainer** | Container Management Platform. | ✅ Live | `http://192.168.3.133:9000` |
| **NGINX Proxy Manager** | Proxy Hosts, SSL and Exposing Services | ✅ Live | `http://192.168.3.133:81` |
| **Heimdall** | Dashboard for Web Services | ✅ Live | `http://192.168.3.133:8080` |
| **Wireguard** | VPN for Remote Access | ✅ Live | `http://192.168.3.133:51820` |

## 📁 Repository Structure

```
homelab-docs/
├── 📄 README.md                 # You are here
```

## 🚧 Current Projects & Goals

-   [ ] **Media Server** Get Jellyfin, qBittorrent, outgoing VPN and *arr stack up and running again.

## 📝 Notes & Log

-   **2025-08-20:** Fresh Install of Ubuntu Server, starting with management tools this time.
-   **2025-08-20:** Nuked the homeserver to start from scratch.
-   **2025-08-19:** Initialized this documentation.

---
*“Never underestimate the raw power of a repurposed gaming PC.”*
