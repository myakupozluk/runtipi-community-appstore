# Letta

Letta (the MemGPT lineage) - an agent server with memory as the core primitive: agents live server-side with self-editing persistent memory, and clients (SDKs, the hosted ADE at app.letta.com) connect to them over the REST API.

## Overview
* **Category:** Development, Games
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
