# Freeboard

Freeboard is a turn-key HTML-based 'engine' for dashboards. Besides a nice looking layout engine, it provides a plugin architecture for creating datasources (which fetch data) and widgets (which display data)— freeboard then does all the work to connect the two together.

## Overview
* **Category:** Development, Data, Automation
* **Default Port:** `8000` (Internal: `80`)
* **Architectures:** amd64, arm64
* **Author / Project:** xneo1/portainer_templates
* **Source:** [https://github.com/xneo1/portainer_templates/](https://github.com/xneo1/portainer_templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
