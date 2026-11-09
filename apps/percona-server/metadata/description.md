# Percona Server

Percona Server for MySQL - a free, fully MySQL-compatible drop-in with extra instrumentation (detailed `INFORMATION_SCHEMA` and `PERFORMANCE_SCHEMA` tables), improved diagnostics, and performance enhancements.

## Overview
* **Category:** Development, Data, Games
* **Default Port:** `3306` (Internal: `3306`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
