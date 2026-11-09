# Umami

Umami v3 - privacy-first web analytics: no cookies, no cross-site tracking, GDPR/PECR-friendly, with a clean dashboard and a ~2 KB tracking script. One stateless container + a managed Postgres (Umami v3 dropped MySQL - Postgres only).

## Overview
* **Category:** Security, Development, Data
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
