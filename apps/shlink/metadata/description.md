# Shlink

Shlink - a self-hosted URL shortener: short links on your own domain with a full REST API, QR codes, rich visit analytics (with optional GeoIP), tags, device-based redirect rules, and link expiration.

## Overview
* **Category:** Development, Data
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
