# Valkey

Valkey - the BSD-licensed, Redis-compatible in-memory data store, forked and stewarded by the Linux Foundation after Redis changed its license. Drop-in for Redis clients: caching, queues, pub/sub, streams, and data structures.

## Overview
* **Category:** Development, Data
* **Default Port:** `6379` (Internal: `6379`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
