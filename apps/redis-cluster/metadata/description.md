# Redis Cluster (stack)

Redis Cluster - horizontally-scaled Redis where the keyspace is partitioned across multiple master shards, each with a replica. This template runs 6 nodes (3 masters + 3 replicas) and a one-shot init that forms the cluster.

## Overview
* **Category:** Development
* **Default Port:** `8080` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
