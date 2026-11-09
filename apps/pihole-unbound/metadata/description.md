# Pi-Hole-Unbound

A Linux network-level advertisement and Internet tracker blocking application which acts as a DNS sinkhole. This version has Ubound software installed on it so you don't need to rely on external DNS providers. When the installation is complete, navigate to your.ip.goes.here:1010/admin. Follow the article here

## Overview
* **Category:** Security, Network, Development
* **Default Port:** `53` (Internal: `53`)
* **Architectures:** amd64, arm64
* **Author / Project:** novaspirit/pi-hosted
* **Source:** [https://github.com/novaspirit/pi-hosted/](https://github.com/novaspirit/pi-hosted/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
