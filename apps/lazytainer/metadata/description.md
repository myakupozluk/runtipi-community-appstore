# Lazytainer

Lazytainer monitors network traffic to containers. If there is traffic, the container runs, otherwise the container is stopped/paused.

## Overview
* **Category:** Network, Productivity
* **Default Port:** `81` (Internal: `81`)
* **Architectures:** amd64, arm64
* **Author / Project:** xneo1/portainer_templates
* **Source:** [https://github.com/xneo1/portainer_templates/](https://github.com/xneo1/portainer_templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
