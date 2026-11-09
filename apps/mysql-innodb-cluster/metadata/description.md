# MySQL InnoDB Cluster

3-node high availability using MySQL Group Replication - the engine that MySQL InnoDB Cluster is built on.

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
