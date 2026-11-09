# FileBrowser (stack)

FileBrowser - a fast web UI over a file volume: upload, organize, preview, edit, and share files via public links, with per-user scopes. Apache-2.0, non-root, ~30 MB of Go.

## Overview
* **Category:** Data
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
