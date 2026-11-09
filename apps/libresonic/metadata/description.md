# libresonic

Libresonic is a free, web-based media streamer, providing ubiqutious access to your music. Use it to share your music with friends, or to listen to your own music while at work. You can stream to multiple players simultaneously, for instance to one player in your kitchen and another in your living room. /music = Location of music. /media = Location of other media. /podcasts = Location of podcasts. /playlists = Location for playlists storage. CONTEXT_PATH is for setting url-base in reverse proxy setups - (optional) Default user/pass is admin/admin

## Overview
* **Category:** Media, Network, Data
* **Default Port:** `4040` (Internal: `4040`)
* **Architectures:** amd64, arm64
* **Author / Project:** dnburgess/self-hosted-template
* **Source:** [https://github.com/dnburgess/self-hosted-template/](https://github.com/dnburgess/self-hosted-template/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
