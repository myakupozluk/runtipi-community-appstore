# Hishtory-server

[hiSHtory](https://github.com/ddworken/hishtory) is a better shell history. It stores your shell history in context (what directory you ran the command in, whether it succeeded or failed, how long it took, etc). This is all stored locally and end-to-end encrypted for syncing to to all your other computers.

## Overview
* **Category:** Development, Data, Games
* **Default Port:** `8080` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** technorabilia/portainer-templates
* **Source:** [https://github.com/technorabilia/portainer-templates/](https://github.com/technorabilia/portainer-templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
