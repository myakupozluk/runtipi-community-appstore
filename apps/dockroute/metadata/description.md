# DockRoute

External-DNS for plain Docker hosts: watches running containers, reads dockroute.* labels and reconciles the matching DNS records — and Cloudflare Tunnel routes — in a pluggable provider. TXT-based ownership means it never alters records it cannot prove it manages. Source: https://github.com/Dockroute/Dockroute

## Overview
* **Category:** Security, Network, Development
* **Default Port:** `8080` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** Community
* **Source:** [https://github.com/runtipi/runtipi](https://github.com/runtipi/runtipi)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
