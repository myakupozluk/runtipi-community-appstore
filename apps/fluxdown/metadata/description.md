# FluxDown

Multi-protocol download manager with a web UI. Handles HTTP/HTTPS, FTP, BitTorrent (DHT/magnet), eD2K/Kad, HLS and DASH, with dynamic file segmentation, token-bucket rate limiting and SQLite-backed resume. Exposes an aria2-compatible JSON-RPC API. GitHub: [zerx-lab/FluxDown](https://github.com/zerx-lab/FluxDown)

## Overview
* **Category:** Development, Data
* **Default Port:** `17800` (Internal: `17800`)
* **Architectures:** amd64, arm64
* **Author / Project:** zerx-lab
* **Source:** [https://github.com/runtipi/runtipi](https://github.com/runtipi/runtipi)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
