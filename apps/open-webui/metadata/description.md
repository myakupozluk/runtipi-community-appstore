# Open WebUI

Open WebUI - the self-hosted AI chat workspace: ChatGPT-style UI over any OpenAI-compatible API, with RAG over uploaded documents, multi-user accounts, RBAC, and prompt/model presets. Single container + volume.

## Overview
* **Category:** Development, Productivity, Social
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
