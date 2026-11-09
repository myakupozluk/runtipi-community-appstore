# ChromaDB

Chroma vector database, single container + volume, internal-only (Chroma has no built-in auth; the project network is the boundary, like the MongoDB template).

## Overview
* **Category:** Security, Network, Development
* **Default Port:** `8000` (Internal: `8000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
