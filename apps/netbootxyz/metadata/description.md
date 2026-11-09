# Netboot.xyz (container)

Netbootxyz is a way to PXE boot various operating system installers or utilities from one place within the BIOS without the need of having to go retrieve the media to run the tool

## Overview
* **Category:** Media, Data
* **Default Port:** `3000` (Internal: `3000`)
* **Architectures:** amd64, arm64
* **Author / Project:** mediadepot/templates
* **Source:** [https://github.com/mediadepot/templates/](https://github.com/mediadepot/templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
