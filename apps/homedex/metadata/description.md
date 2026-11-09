# Homedex

Read-only inventory for your homelab: services, hosts, ports, routes, certificates, domains and changes, discovered from Docker, Proxmox VE, Tailscale and your reverse proxy. It never starts, stops or reconfigures anything. Source: https://github.com/HarshShah0203/homedex

## Overview
* **Category:** Security, Network, Development
* **Default Port:** `9993` (Internal: `9993`)
* **Architectures:** amd64, arm64
* **Author / Project:** HarshShah0203/homedex
* **Source:** [https://github.com/HarshShah0203/homedex/](https://github.com/HarshShah0203/homedex/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
