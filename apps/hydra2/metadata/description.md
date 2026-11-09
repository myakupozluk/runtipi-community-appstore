# hydra2

NZBHydra is a meta search for NZB indexers and the "spiritual successor" to NZBmegasearcH. It provides easy access to a number of raw and newznab based indexers.

## Overview
* **Category:** Development, Data
* **Default Port:** `5076` (Internal: `5076`)
* **Architectures:** amd64, arm64
* **Author / Project:** dnburgess/self-hosted-template
* **Source:** [https://github.com/dnburgess/self-hosted-template/](https://github.com/dnburgess/self-hosted-template/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
