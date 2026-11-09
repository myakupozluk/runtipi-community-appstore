# Kilo (headless)

Kilo, open-source AI coding agent, running in server mode (`kilo serve`) on Miget: a persistent remote agent whose HTTP+SSE API your Kilo clients attach to (IDE extension, `kilo attach`, or the Cloud Agents web UI via Remote Connections).

## Overview
* **Category:** Development, Data, Games
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
