# Boinc

[BOINC](https://boinc.berkeley.edu/) is a platform for high-throughput computing on a large scale (thousands or millions of computers). It can be used for volunteer computing (using consumer devices) or grid computing (using organizational resources). It supports virtualized, parallel, and GPU-based applications.

## Overview
* **Category:** Development
* **Default Port:** `8080` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** technorabilia/portainer-templates
* **Source:** [https://github.com/technorabilia/portainer-templates/](https://github.com/technorabilia/portainer-templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
