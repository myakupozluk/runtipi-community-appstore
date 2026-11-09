# Dozzle

Dozzle is a small lightweight application with a web based interface to monitor Docker logs. It doesn’t store any log files. It is for live monitoring of your container logs only.

## Overview
* **Category:** Productivity, Data, Monitoring
* **Default Port:** `8888` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** xneo1/portainer_templates
* **Source:** [https://github.com/xneo1/portainer_templates/](https://github.com/xneo1/portainer_templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
