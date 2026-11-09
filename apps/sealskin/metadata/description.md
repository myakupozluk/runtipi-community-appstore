# Sealskin

[Sealskin](https://github.com/selkies-project/sealskin/) is a self-hosted browser isolation and remote application streaming platform. It runs desktop applications in isolated containers on a server you control and streams them to any browser or phone. Clients include a browser extension, mobile apps, and a web app served by the server itself. Each turns links, files, downloads, and text selections into something you open remotely instead of locally, so nothing from the web runs on the device in front of you.

## Overview
* **Category:** Media, Development, Productivity
* **Default Port:** `8443` (Internal: `8443`)
* **Architectures:** amd64, arm64
* **Author / Project:** technorabilia/portainer-templates
* **Source:** [https://github.com/technorabilia/portainer-templates/](https://github.com/technorabilia/portainer-templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
