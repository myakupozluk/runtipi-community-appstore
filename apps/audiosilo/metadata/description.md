# Audiosilo

[AudioSilo](https://audiosilo.app) is a self-hosted audiobook server. Point it at your audiobook folders and listen from the built-in web player or the AudioSilo apps for iOS and Android, with listening progress synced across devices.

## Overview
* **Category:** Media, Development, Data
* **Default Port:** `8080` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** technorabilia/portainer-templates
* **Source:** [https://github.com/technorabilia/portainer-templates/](https://github.com/technorabilia/portainer-templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
