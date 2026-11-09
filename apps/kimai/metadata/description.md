# Kimai

[Kimai](https://kimai.org/) is a professional grade time-tracking application, free and open-source. It handles use-cases of freelancers as well as companies with dozens or hundreds of users. Kimai was build to track your project times and ships with many advanced features, including but not limited to: JSON API, invoicing, data exports, multi-timer and punch-in punch-out mode, tagging, multi-user - multi-timezones - multi-language ([over 30 translations existing](https://hosted.weblate.org/projects/kimai/)!), authentication via SAML/LDAP/Database, two-factor authentication (2FA) with TOTP, customizable role and team permissions, responsive design, user/customer/project specific rates, advanced search & filtering, money and time budgets, advanced reporting, support for [plugins](https://www.kimai.org/store/) and so much more.

## Overview
* **Category:** Security, Development, Productivity
* **Default Port:** `80` (Internal: `80`)
* **Architectures:** amd64, arm64
* **Author / Project:** technorabilia/portainer-templates
* **Source:** [https://github.com/technorabilia/portainer-templates/](https://github.com/technorabilia/portainer-templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
