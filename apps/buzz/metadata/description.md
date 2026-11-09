# Buzz

Buzz - a self-hosted workspace where humans and AI agents share the same rooms. Under the hood it is a Nostr relay: every message, reaction, workflow step, review approval, and git event is a signed event in one log, whether the author is

## Overview
* **Category:** Security, Development, Productivity
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
