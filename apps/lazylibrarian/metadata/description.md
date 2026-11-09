# Lazylibrarian

[Lazylibrarian](https://lazylibrarian.gitlab.io/) is a program to follow authors and grab metadata for all your digital reading needs. It uses a combination of HardCover, OpenLibrary, Librarything, GoodReads, and optionally GoogleBooks as sources for author info and book info.

## Overview
* **Category:** Security, Media, Development
* **Default Port:** `5299` (Internal: `5299`)
* **Architectures:** amd64, arm64
* **Author / Project:** technorabilia/portainer-templates
* **Source:** [https://github.com/technorabilia/portainer-templates/](https://github.com/technorabilia/portainer-templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
