# MariaDB Replication

Asynchronous MariaDB replication: one primary accepts writes and streams its binary log to a read-only replica. This is the classic read-scaling / hot-standby topology.

## Overview
* **Category:** Development, Data
* **Default Port:** `3307` (Internal: `3306`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
