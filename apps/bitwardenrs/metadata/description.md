# Bitwarden RS

This is a Bitwarden server API implementation written in Rust compatible with upstream Bitwarden clients*, perfect for self-hosted deployment where running the official resource-heavy service might not be ideal..

## Overview
* **Category:** Development, Games
* **Default Port:** `80` (Internal: `80`)
* **Architectures:** amd64, arm64
* **Author / Project:** mikestraney/portainer-templates
* **Source:** [https://github.com/mikestraney/portainer-templates/](https://github.com/mikestraney/portainer-templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
