# RustFS

S3-compatible object storage written in Rust, an open-source alternative to MinIO, with a web console for browsing buckets and managing users, policies and access keys. Source: https://github.com/rustfs/rustfs

## Overview
* **Category:** Development, Data
* **Default Port:** `8080` (Internal: `8000`)
* **Architectures:** amd64, arm64
* **Author / Project:** NotAFlightRisk/portainer-templates-extras
* **Source:** [https://github.com/NotAFlightRisk/portainer-templates-extras/](https://github.com/NotAFlightRisk/portainer-templates-extras/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
