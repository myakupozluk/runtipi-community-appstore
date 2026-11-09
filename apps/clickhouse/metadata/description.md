# ClickHouse Cluster

3-node ClickHouse cluster, one shard, three replicas, with embedded ClickHouse Keeper (no separate ZooKeeper pods). Internal-only; 20 GB per node.

## Overview
* **Category:** Development, Data
* **Default Port:** `8123` (Internal: `8123`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
