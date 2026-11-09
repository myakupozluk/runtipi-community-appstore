# Ferret

Self-hosted home inventory: find anything you own. Photos, barcodes, QR labels, warranties, maintenance and an insurance report, with a REST API, an MCP server and optional AI on your own models.

## Overview
* **Category:** Media, Development, Productivity
* **Default Port:** `8787` (Internal: `8787`)
* **Architectures:** amd64, arm64
* **Author / Project:** ferret-project/ferret
* **Source:** [https://github.com/ferret-project/ferret/](https://github.com/ferret-project/ferret/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
