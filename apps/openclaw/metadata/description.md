# OpenClaw

OpenClaw, an autonomous AI agent you run yourself: web dashboard, scheduled tasks, plugins, persistent workspace. This template uses the coollabsio all-in-one image (nginx + gateway, env-driven).

## Overview
* **Category:** Network, Productivity, Data
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
