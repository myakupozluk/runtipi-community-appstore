# Pelorus

[Pelorus](https://github.com/linuxserver/pelorus) is an AI navigator for Selkies-powered Linux desktops. Pelorus runs a FastAPI server that gives an LLM agent (Ollama, OpenAI-compatible, or Gemini) control over mouse, keyboard, screenshot, and window management via the [Pixelflux computer-use backend](https://github.com/linuxserver/pixelflux#computer-use-interface-wayland), a Linux accessibility tree (AT-SPI), and optional KWin D-Bus integration.

## Overview
* **Category:** Development, Games
* **Default Port:** `3001` (Internal: `3001`)
* **Architectures:** amd64, arm64
* **Author / Project:** technorabilia/portainer-templates
* **Source:** [https://github.com/technorabilia/portainer-templates/](https://github.com/technorabilia/portainer-templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
