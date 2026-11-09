# LiveKit Agents

A voice AI agent worker on the LiveKit Agents framework: it joins LiveKit rooms and converses - Deepgram for ears, ElevenLabs for voice, any OpenAI-compatible LLM for the brain (the catalogue's `litellm` gateway slots in via

## Overview
* **Category:** Network
* **Default Port:** `8080` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
