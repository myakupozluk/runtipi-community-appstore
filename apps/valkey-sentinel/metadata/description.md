# Valkey Sentinel

High availability for Valkey with automatic failover, using Valkey's built-in Sentinel (the same design as Redis Sentinel). One master, two replicas, and three sentinels that watch the master and promote a replica if it fails.

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
