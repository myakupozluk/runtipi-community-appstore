# Plausible

Plausible - privacy-friendly web analytics: a lightweight, cookie-free, open-source Google Analytics alternative. A clean single-page dashboard, no personal data collection, no consent banner needed, and a script ~75x smaller than GA.

## Overview
* **Category:** Security, Data, Monitoring
* **Default Port:** `5000` (Internal: `5000`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
