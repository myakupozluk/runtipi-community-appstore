# AudioMuse-AI

Automatic playlist generation for self-hosted music servers. Analyses your library locally to group tracks by how they sound. Works with Navidrome, Jellyfin, LMS, Lyrion, Emby and Plex. GitHub: [NeptuneHub/AudioMuse-AI](https://github.com/NeptuneHub/AudioMuse-AI)

## Overview
* **Category:** Media, Development, Games
* **Default Port:** `8080` (Internal: `8000`)
* **Architectures:** amd64, arm64
* **Author / Project:** Community
* **Source:** [https://github.com/runtipi/runtipi](https://github.com/runtipi/runtipi)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
