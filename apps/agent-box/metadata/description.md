# Agent Box

Remote AI coding agents on Miget: a persistent box with Claude Code, opencode and Kilo CLI preinstalled, reachable from any browser as a web terminal (ttyd + tmux) behind basic auth.

## Overview
* **Category:** Security, Development
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
