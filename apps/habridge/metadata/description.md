# Habridge

[Habridge](https://github.com/bwssytems/ha-bridge/) emulates Philips Hue API to other home automation gateways such as an Amazon Echo/Dot Gen 1 (gen 2 has issues discovering ha-bridge) or other systems that support Philips Hue. The Bridge handles basic commands such as On, Off and brightness commands of the hue protocol. This bridge can control most devices that have a distinct API.

## Overview
* **Category:** Network, Development, Automation
* **Default Port:** `8080` (Internal: `8080`)
* **Architectures:** amd64, arm64
* **Author / Project:** technorabilia/portainer-templates
* **Source:** [https://github.com/technorabilia/portainer-templates/](https://github.com/technorabilia/portainer-templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
