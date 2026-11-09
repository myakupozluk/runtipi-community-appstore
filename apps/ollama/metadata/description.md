# Ollama

Ollama - run open large language models locally behind a simple HTTP API. Pull a model (Llama, Mistral, Qwen, Gemma, Phi, and many more) and serve it from your own infrastructure, with OpenAI-compatible endpoints.

## Overview
* **Category:** Development
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
