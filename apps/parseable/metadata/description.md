# Parseable

Parseable - a single-binary log lake built for object storage: ingest logs over HTTP, store them as compressed Parquet on S3, query with SQL. Rust, lean (runs in 512 MB), and S3-native by design - a natural fit for Miget Buckets.

## Overview
* **Category:** Development, Data, Monitoring
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
