# qFlood

A docker image with qBittorrent and the Flood UI, also optional WireGuard VPN support. See the official documentation for WireGuard VPN support at https://hotio.dev/containers/qflood/

## Overview
* **Category:** Security, Development, Productivity
* **Default Port:** `3000` (Internal: `3000`)
* **Architectures:** amd64, arm64
* **Author / Project:** novaspirit/pi-hosted
* **Source:** [https://github.com/novaspirit/pi-hosted/](https://github.com/novaspirit/pi-hosted/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
