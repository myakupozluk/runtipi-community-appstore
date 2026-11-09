# Karakeep

Karakeep (formerly Hoarder) - a self-hosted "bookmark everything" app: save links, notes, and images, and it automatically crawls and archives the page (so your links never rot), takes a screenshot, full-text indexes everything, and can

## Overview
* **Category:** Media, Productivity
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
