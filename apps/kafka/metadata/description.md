# Apache Kafka

3-node Apache Kafka cluster in KRaft mode (no ZooKeeper) with Kafbat UI, deployable locally with plain Docker Compose or to Miget as a compose stack.

## Overview
* **Category:** Media, Productivity, Social
* **Default Port:** `9092` (Internal: `9092`)
* **Architectures:** amd64, arm64
* **Author / Project:** deployable-sh/stacks
* **Source:** [https://github.com/deployable-sh/stacks/](https://github.com/deployable-sh/stacks/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
