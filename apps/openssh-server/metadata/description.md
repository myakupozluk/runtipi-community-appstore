# Openssh-server

[Openssh-server](https://www.openssh.com/) is a sandboxed environment that allows ssh access without giving keys to the entire server. Giving ssh access via private key often means giving full access to the server. This container creates a limited and sandboxed environment that others can ssh into. The users only have access to the folders mapped and the processes running inside this container.

## Overview
* **Category:** Development, Games
* **Default Port:** `2222` (Internal: `2222`)
* **Architectures:** amd64, arm64
* **Author / Project:** technorabilia/portainer-templates
* **Source:** [https://github.com/technorabilia/portainer-templates/](https://github.com/technorabilia/portainer-templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
