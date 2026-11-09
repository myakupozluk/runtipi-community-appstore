# Jellyfin-Accounts

jfa-go is a user management app for Jellyfin (and now Emby) that provides invite-based account creation as well as other features that make one's instance much easier to manage.

## Overview
* **Category:** Media, Development
* **Default Port:** `8056` (Internal: `8056`)
* **Architectures:** amd64, arm64
* **Author / Project:** novaspirit/pi-hosted
* **Source:** [https://github.com/novaspirit/pi-hosted/](https://github.com/novaspirit/pi-hosted/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
