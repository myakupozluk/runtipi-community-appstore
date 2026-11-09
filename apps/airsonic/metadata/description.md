# Airsonic (container)

Airsonic is a free, web-based media streamer, providing ubiqutious access to your music. Use it to share your music with friends, or to listen to your own music while at work. You can stream to multiple players simultaneously, for instance to one player in your kitchen and another in your living room.

## Overview
* **Category:** Media
* **Default Port:** `4040` (Internal: `4040`)
* **Architectures:** amd64, arm64
* **Author / Project:** Qballjos/portainer_templates
* **Source:** [https://github.com/Qballjos/portainer_templates/](https://github.com/Qballjos/portainer_templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
