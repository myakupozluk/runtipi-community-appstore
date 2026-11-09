# Seerr

Request manager for Jellyfin, Plex and Emby, where people ask for films and shows and Sonarr and Radarr fetch them. It's the merged successor to Overseerr and Jellyseerr. Source: https://github.com/seerr-team/seerr

## Overview
* **Category:** Media, Development
* **Default Port:** `5055` (Internal: `5055`)
* **Architectures:** amd64, arm64
* **Author / Project:** NotAFlightRisk/portainer-templates-extras
* **Source:** [https://github.com/NotAFlightRisk/portainer-templates-extras/](https://github.com/NotAFlightRisk/portainer-templates-extras/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
