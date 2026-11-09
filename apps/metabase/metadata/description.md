# Metabase

Metabase OSS - the BI tool non-analysts actually use: point-and-click questions, dashboards, and SQL when you want it. One JVM container + a managed Postgres for the app database.

## Overview
* **Category:** Development, Data, Finance
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
