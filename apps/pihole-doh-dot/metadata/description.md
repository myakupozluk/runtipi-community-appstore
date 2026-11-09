# Pi-Hole DoH/DoT

A Linux network-level advertisement and Internet tracker blocking application which acts as a DNS sinkhole with both DoH (DNS over HTTPS) and DoT (DNS over TLS) clients.

## Overview
* **Category:** Security, Network
* **Default Port:** `53` (Internal: `53`)
* **Architectures:** amd64, arm64
* **Author / Project:** novaspirit/pi-hosted
* **Source:** [https://github.com/novaspirit/pi-hosted/](https://github.com/novaspirit/pi-hosted/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
