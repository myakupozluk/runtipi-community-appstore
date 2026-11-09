# Maintainerr

Library tidier for Plex, Jellyfin and Emby. You write rules like "nobody's watched it in six months", it gathers what matches into a leaving-soon collection, then has Sonarr and Radarr delete it once the grace period's up. Source: https://github.com/Maintainerr/Maintainerr

## Overview
* **Category:** Media, Development
* **Default Port:** `6246` (Internal: `6246`)
* **Architectures:** amd64, arm64
* **Author / Project:** NotAFlightRisk/portainer-templates-extras
* **Source:** [https://github.com/NotAFlightRisk/portainer-templates-extras/](https://github.com/NotAFlightRisk/portainer-templates-extras/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
