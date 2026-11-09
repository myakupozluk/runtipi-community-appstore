# Qdrant

Qdrant vector database, single container + volume, internal-only by default (no API key is configured; the project network is the boundary).

## Overview
* **Category:** Network, Development, Productivity
* **Default Port:** `6333` (Internal: `6333`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
