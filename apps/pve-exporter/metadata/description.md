# pve-exporter

This is an exporter that exposes information gathered from Proxmox VE node for use by the Prometheus monitoring system.

## Overview
* **Category:** Monitoring
* **Default Port:** `9221` (Internal: `9221`)
* **Architectures:** amd64, arm64
* **Author / Project:** xneo1/portainer_templates
* **Source:** [https://github.com/xneo1/portainer_templates/](https://github.com/xneo1/portainer_templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
