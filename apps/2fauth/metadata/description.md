# 2FAuth

Web app for your two-factor authentication codes, a self-hosted stand-in for Google Authenticator: add accounts by scanning or uploading their QR codes, then copy codes from any browser. Source: https://github.com/Bubka/2FAuth

## Overview
* **Category:** Security, Development
* **Default Port:** `8080` (Internal: `8000`)
* **Architectures:** amd64, arm64
* **Author / Project:** NotAFlightRisk/portainer-templates-extras
* **Source:** [https://github.com/NotAFlightRisk/portainer-templates-extras/](https://github.com/NotAFlightRisk/portainer-templates-extras/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
