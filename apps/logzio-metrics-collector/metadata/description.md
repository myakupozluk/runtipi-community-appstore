# Logzio Metrics Collector

Docker Metrics Collector is a container that runs Metricbeat with the modules you enable at runtime.

## Overview
* **Category:** Productivity, Monitoring
* **Default Port:** `8080` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** mediadepot/templates
* **Source:** [https://github.com/mediadepot/templates/](https://github.com/mediadepot/templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
