# Forgejo Runner

A Forgejo Actions runner in `host` mode - CI for your self-hosted Forgejo or for Codeberg, with jobs running as shell steps in this container (no Docker daemon needed). GitHub-Actions-compatible workflow syntax.

## Overview
* **Category:** Development, Productivity
* **Default Port:** `8080` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
