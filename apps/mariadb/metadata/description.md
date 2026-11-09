# MariaDB (stack)

MariaDB 11.8 - the community-developed MySQL fork, as a single self-hosted node. Drop-in compatible with MySQL for most applications, configured through the official image's environment variables, with data on a volume.

## Overview
* **Category:** Development, Data
* **Default Port:** `3306` (Internal: `3306`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
