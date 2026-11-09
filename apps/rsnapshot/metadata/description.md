# Rsnapshot

[Rsnapshot](http://www.rsnapshot.org/) is a filesystem snapshot utility based on rsync. rsnapshot makes it easy to make periodic snapshots of local machines, and remote machines over ssh. The code makes extensive use of hard links whenever possible, to greatly reduce the disk space required.

## Overview
* **Category:** Development, Data
* **Default Port:** `80` (Internal: `80`)
* **Architectures:** amd64, arm64
* **Author / Project:** technorabilia/portainer-templates
* **Source:** [https://github.com/technorabilia/portainer-templates/](https://github.com/technorabilia/portainer-templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
