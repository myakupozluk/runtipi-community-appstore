# Redis (stack)

Redis - the in-memory data store used for caching, queues, pub/sub, streams, rate-limiting, and rich data structures. This is a single node, password-protected, with append-only persistence on a volume.

## Overview
* **Category:** Security, Development, Data
* **Default Port:** `6379` (Internal: `6379`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
