# TEI Embeddings

TEI - Hugging Face's Rust embeddings server: small models like `BAAI/bge-small-en-v1.5` (384-dim) serve real RAG workloads from CPU in ~512 MB, over both TEI's native API and an OpenAI-compatible `/v1/embeddings` endpoint.

## Overview
* **Category:** Development, Games
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
