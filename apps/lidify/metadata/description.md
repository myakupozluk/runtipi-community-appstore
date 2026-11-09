# Lidify

Self-hosted, on-demand audio streaming platform that brings the Spotify experience to your personal music library. Features music streaming, podcast subscriptions, audiobook integration, playlist generation, and Lidarr integration for music discovery.

## Overview
* **Category:** Media
* **Default Port:** `8080` (Internal: `3006`)
* **Architectures:** amd64, arm64
* **Author / Project:** xneo1/portainer_templates
* **Source:** [https://github.com/xneo1/portainer_templates/](https://github.com/xneo1/portainer_templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
