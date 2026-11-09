# Hermes Agent

Hermes Agent (Nous Research), a self-improving AI agent with a learning loop (skills from experience), cron, hooks, and a web dashboard. Official image, single container + `/opt/data` volume (sessions, memories, skills, config all persist).

## Overview
* **Category:** Development, Data, Monitoring
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
