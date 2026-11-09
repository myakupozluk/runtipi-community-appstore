# Supabase Nano

supabase-lite squeezed into a 1 GiB plan - the same six services (Postgres, Auth, REST, Kong, Studio, postgres-meta), memory- tuned until the whole stack, dashboard included, allocates exactly 1024 MiB.

## Overview
* **Category:** Security, Development, Monitoring
* **Default Port:** `3000` (Internal: `3000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
