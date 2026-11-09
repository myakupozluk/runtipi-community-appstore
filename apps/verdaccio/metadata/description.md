# Verdaccio

Private npm registry and caching proxy: publish your own packages to it, and install everything else through it so npmjs downloads get cached locally. Works with npm, yarn and pnpm. Source: https://github.com/verdaccio/verdaccio

## Overview
* **Category:** Network, Development, Data
* **Default Port:** `4873` (Internal: `4873`)
* **Architectures:** amd64, arm64
* **Author / Project:** NotAFlightRisk/portainer-templates-extras
* **Source:** [https://github.com/NotAFlightRisk/portainer-templates-extras/](https://github.com/NotAFlightRisk/portainer-templates-extras/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
