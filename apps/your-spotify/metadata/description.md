# Your_spotify (container)

[Your_spotify](https://github.com/Yooooomi/your_spotify) is a self-hosted application that tracks what you listen and offers you a dashboard to explore statistics about it! It's composed of a web server which polls the Spotify API every now and then and a web application on which you can explore your statistics.

## Overview
* **Category:** Media, Development, Monitoring
* **Default Port:** `80` (Internal: `80`)
* **Architectures:** amd64, arm64
* **Author / Project:** technorabilia/portainer-templates
* **Source:** [https://github.com/technorabilia/portainer-templates/](https://github.com/technorabilia/portainer-templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
