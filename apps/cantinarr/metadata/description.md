# Cantinarr

Media requests and server management in one app. Household members browse and request movies, shows, books, and music, follow downloads, and get notified when content is ready. Administrators manage Radarr, Sonarr, Chaptarr, Lidarr, and download clients, review approvals, and investigate stuck downloads. AI is optional, and authorized MCP clients can use the same server. GitHub: [windoze95/cantinarr](https://github.com/windoze95/cantinarr)

## Overview
* **Category:** Security, Media, Development
* **Default Port:** `8585` (Internal: `8585`)
* **Architectures:** amd64, arm64
* **Author / Project:** Community
* **Source:** [https://github.com/runtipi/runtipi](https://github.com/runtipi/runtipi)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
