# Factorio Server

Headless Factorio via factoriotools/factorio - the community-standard image. Saves, mods, and server settings live on the `/factorio` volume; a new map generates on first boot and the latest save loads thereafter.

## Overview
* **Category:** Automation, Games
* **Default Port:** `34197` (Internal: `34197`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
