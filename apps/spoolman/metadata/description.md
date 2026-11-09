# Spoolman

3D printer filament tracker that keeps count of your spools, what's left on each and where they live, makes printable QR labels, and takes usage straight from Moonraker (Klipper) or OctoPrint as you print. Source: https://github.com/Donkie/Spoolman

## Overview
* **Category:** Development
* **Default Port:** `7912` (Internal: `8000`)
* **Architectures:** amd64, arm64
* **Author / Project:** NotAFlightRisk/portainer-templates-extras
* **Source:** [https://github.com/NotAFlightRisk/portainer-templates-extras/](https://github.com/NotAFlightRisk/portainer-templates-extras/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
