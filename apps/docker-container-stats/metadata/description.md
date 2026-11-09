# Docker Container Stats

Docker Container Stats is a web interface for viewing historical and current statistics per docker container (cpu, mem, net i/o, block i/o) - in a docker container.

## Overview
* **Category:** Productivity
* **Default Port:** `8383` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** xneo1/portainer_templates
* **Source:** [https://github.com/xneo1/portainer_templates/](https://github.com/xneo1/portainer_templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
