# HomeLab Monitor

Self-hosted homelab dashboard, one container. Per-container GPU/VRAM attribution (which process holds the card, not just total load), Docker health/logs, systemd status, host vitals (CPU/RAM/disk/temps), multiple hosts over SSH. Alerts via Discord/ntfy/Telegram. Read-only MCP server on :9810. MIT. Source: https://github.com/SikamikanikoBG/homelab-monitor

## Overview
* **Category:** Development, Productivity, Monitoring
* **Default Port:** `8080` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** Community
* **Source:** [https://github.com/runtipi/runtipi](https://github.com/runtipi/runtipi)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
