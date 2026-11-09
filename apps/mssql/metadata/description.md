# SQL Server (stack)

Official SQL Server on Linux container (SQL Server 2025), Express edition by default - the edition Microsoft licenses for production at no cost. Single node + 10 GB volume, internal-only (databases never get a public domain).

## Overview
* **Category:** Development, Data, Games
* **Default Port:** `1433` (Internal: `1433`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
