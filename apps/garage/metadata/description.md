# Garage

Garage - the S3-compatible object store the self-hosting community moved to after MinIO archived its open source in 2026: a single static Rust binary, AGPL, actively released, designed for exactly this job.

## Overview
* **Category:** Data
* **Default Port:** `3900` (Internal: `3900`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
