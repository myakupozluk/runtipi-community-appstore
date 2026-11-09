# Mattermost

Mattermost - open-source team chat: channels, threads, DMs, voice calls, slash commands, integrations, and plugins. Team Edition image on a managed Postgres - it listens on :5000 directly, so no proxy.

## Overview
* **Category:** Network, Development, Social
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
