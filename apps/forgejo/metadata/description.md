# Forgejo (container)

A self-hosted lightweight software forge, providing Git hosting, code review, issue tracking, and CI/CD. Source: https://codeberg.org/forgejo/forgejo

## Overview
* **Category:** Development
* **Default Port:** `3000` (Internal: `3000`)
* **Architectures:** amd64, arm64
* **Author / Project:** Community
* **Source:** [https://github.com/runtipi/runtipi](https://github.com/runtipi/runtipi)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
