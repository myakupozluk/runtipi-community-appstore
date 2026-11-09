# Cardigann

Cardigann, a server for adding extra indexers to Sonarr, SickRage and CouchPotato via Torznab and TorrentPotato proxies. Behind the scenes Cardigann logs in and runs searches and then transforms the results into a compatible format.

## Overview
* **Category:** Media, Data, Monitoring
* **Default Port:** `5060` (Internal: `5060`)
* **Architectures:** amd64, arm64
* **Author / Project:** mediadepot/templates
* **Source:** [https://github.com/mediadepot/templates/](https://github.com/mediadepot/templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
