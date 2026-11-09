# Cloudflared-web

A docker image that packages both cloudflared cli and a simple Web UI to easily start or stop remotely-managed Cloudflare tunnel. Source: https://github.com/WisdomSky/Cloudflared-web

## Overview
* **Category:** Network, Development, Productivity
* **Default Port:** `8080` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** Community
* **Source:** [https://github.com/runtipi/runtipi](https://github.com/runtipi/runtipi)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
