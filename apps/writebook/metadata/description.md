# Writebook

Writebook - 37signals' free, self-hosted publishing tool: write and share books, manuals, and documentation with a clean, fast reader. It is a Rails app (the same stack behind Basecamp and HEY) fronted by Thruster, 37signals' HTTP/2 proxy.

## Overview
* **Category:** Media, Network, Productivity
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
