# Penpot

Penpot - the open-source design and prototyping platform (the Figma alternative): SVG-native, web-based, with real design-to-dev handoff. MPL-2.0. Frontend + backend + exporter on a managed Postgres and a noeviction Valkey.

## Overview
* **Category:** Development
* **Default Port:** `8080` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
