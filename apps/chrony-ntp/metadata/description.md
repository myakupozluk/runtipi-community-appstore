# Chrony NTP

chrony is a versatile implementation of the Network Time Protocol (NTP). It can synchronise the system clock with NTP servers, reference clocks (e.g. GPS receiver), and manual input using wristwatch and keyboard. It can also operate as an NTPv4 (RFC 5905) server and peer to provide a time service to other computers in the network.

## Overview
* **Category:** Network, Development, Data
* **Default Port:** `123` (Internal: `123`)
* **Architectures:** amd64, arm64
* **Author / Project:** novaspirit/pi-hosted
* **Source:** [https://github.com/novaspirit/pi-hosted/](https://github.com/novaspirit/pi-hosted/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
