# Deluge openvpn

This container contains OpenVPN and Deluge with a configuration where Deluge is running only when OpenVPN has an active tunnel. It bundles configuration files for many popular VPN providers to make the setup easier.

## Overview
* **Category:** Security, Network, Development
* **Default Port:** `8112` (Internal: `8112`)
* **Architectures:** amd64, arm64
* **Author / Project:** SelfhostedPro/selfhosted_templates
* **Source:** [https://github.com/SelfhostedPro/selfhosted_templates/](https://github.com/SelfhostedPro/selfhosted_templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
