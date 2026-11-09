# Minecraft Server (container)

This docker image provides a Minecraft Server that will automatically download the latest stable version at startup. You can also run/upgrade to any specific version or the latest snapshot. See the Versions section below for more information.

## Overview
* **Category:** Development, Productivity, Data
* **Default Port:** `25565` (Internal: `25565`)
* **Architectures:** amd64, arm64
* **Author / Project:** novaspirit/pi-hosted
* **Source:** [https://github.com/novaspirit/pi-hosted/](https://github.com/novaspirit/pi-hosted/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
