# Supabase Lite

The budget cut of the supabase template: Postgres, Auth (GoTrue) and REST (PostgREST) behind the Kong gateway - the four services most Supabase apps actually use - plus the Studio dashboard. No Realtime, Storage, edge functions or pooler.

## Overview
* **Category:** Security, Network, Development
* **Default Port:** `3000` (Internal: `3000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
