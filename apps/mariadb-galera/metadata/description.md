# MariaDB Galera

3-node MariaDB 11.8 LTS cluster with Galera synchronous multi-primary replication - every node accepts writes, any node can die. Runs the OFFICIAL mariadb image (the Galera library ships in it); clustering is pure command-line flags.

## Overview
* **Category:** Development, Data
* **Default Port:** `8080` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
