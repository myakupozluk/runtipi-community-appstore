# Transmission OpenVPN Latest

This container contains OpenVPN and Transmission with a configuration where Transmission is running only when OpenVPN has an active tunnel. It bundles configuration files for many popular VPN providers to make the setup easier.

## Overview
* **Category:** Security, Network, Development
* **Default Port:** `9091` (Internal: `9091`)
* **Architectures:** amd64, arm64
* **Author / Project:** novaspirit/pi-hosted
* **Source:** [https://github.com/novaspirit/pi-hosted/](https://github.com/novaspirit/pi-hosted/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
