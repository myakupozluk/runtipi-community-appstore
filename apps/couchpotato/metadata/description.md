# CouchPotato

CouchPotato (CP) is an automatic NZB and torrent downloader. You can keep a "movies I want"-list and it will search for NZBs/torrents of these movies every X hours. Once a movie is found, it will send it to SABnzbd or download the torrent to a specified directory.

## Overview
* **Category:** Media, Development, Data
* **Default Port:** `5050` (Internal: `5050`)
* **Architectures:** amd64, arm64
* **Author / Project:** xneo1/portainer_templates
* **Source:** [https://github.com/xneo1/portainer_templates/](https://github.com/xneo1/portainer_templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
