# Tvheadend

[Tvheadend](https://www.tvheadend.org/) works as a proxy server: is a TV streaming server and recorder for Linux, FreeBSD and Android supporting DVB-S, DVB-S2, DVB-C, DVB-T, ATSC, ISDB-T, IPTV, SAT>IP and HDHomeRun as input sources. Tvheadend offers the HTTP (VLC, MPlayer), HTSP (Kodi, Movian) and SAT>IP streaming. Multiple EPG sources are supported (over-the-air DVB and ATSC including OpenTV DVB extensions, XMLTV, PyXML).

## Overview
* **Category:** Media, Network, Games
* **Default Port:** `9981` (Internal: `9981`)
* **Architectures:** amd64, arm64
* **Author / Project:** technorabilia/portainer-templates
* **Source:** [https://github.com/technorabilia/portainer-templates/](https://github.com/technorabilia/portainer-templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
