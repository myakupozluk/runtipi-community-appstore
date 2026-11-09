# Shiori (container)

Shiori is a simple bookmarks manager written in Go language. Intended as a simple clone of Pocket. You can use it as command line application or as web application.

## Overview
* **Category:** Media
* **Default Port:** `7564` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** novaspirit/pi-hosted
* **Source:** [https://github.com/novaspirit/pi-hosted/](https://github.com/novaspirit/pi-hosted/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
