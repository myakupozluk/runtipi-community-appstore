# Netdata

Troubleshoot slowdowns and anomalies in your infrastructure with thousands of per-second metrics, meaningful visualizations, and insightful health alarms with zero configuration.

## Overview
* **Category:** Data, Monitoring
* **Default Port:** `19999` (Internal: `19999`)
* **Architectures:** amd64, arm64
* **Author / Project:** novaspirit/pi-hosted
* **Source:** [https://github.com/novaspirit/pi-hosted/](https://github.com/novaspirit/pi-hosted/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
