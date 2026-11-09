# Etherpad

Collaborative text editor where everyone types in the same document at once, with history, chat and plugins. This one runs on Postgres. Source: https://github.com/ether/etherpad

## Overview
* **Category:** Development, Productivity, Social
* **Default Port:** `8080` (Internal: `8000`)
* **Architectures:** amd64, arm64
* **Author / Project:** NotAFlightRisk/portainer-templates-extras
* **Source:** [https://github.com/NotAFlightRisk/portainer-templates-extras/](https://github.com/NotAFlightRisk/portainer-templates-extras/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
