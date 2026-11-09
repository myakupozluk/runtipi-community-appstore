# systemprompt

Self-owned AI control plane: governance gateway for Claude, OpenAI, and Gemini with policy checks, audit, rate limits, and MCP orchestration. Bundles Postgres. GitHub: [systempromptio/systemprompt-template](https://github.com/systempromptio/systemprompt-template)

## Overview
* **Category:** Network, Development
* **Default Port:** `8080` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** Community
* **Source:** [https://github.com/runtipi/runtipi](https://github.com/runtipi/runtipi)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
