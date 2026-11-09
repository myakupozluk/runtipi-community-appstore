# Cops

[Cops](https://github.com/mikespub-org/seblucas-cops) by Sébastien Lucas, now maintained by MikesPub, stands for Calibre OPDS (and HTML) Php Server. COPS links to your Calibre library database and allows downloading and emailing of books directly from a web browser and provides a OPDS feed to connect to your devices. Changes in your Calibre library are reflected immediately in your COPS pages. See : [COPS's home](https://github.com/mikespub-org/seblucas-cops) for more details. Don't forget to check the [Wiki](https://github.com/mikespub-org/seblucas-cops/wiki). ## Why? (taken from the author's site) In my opinion Calibre is a marvelous tool but is too big and has too much dependencies to be used for its content server. That's the main reason why I coded this OPDS server. I needed a simple tool to be installed on a small server (Seagate Dockstar in my case). I initially thought of Calibre2OPDS but as it generate static file no search was possible. Later I added an simple HTML catalog that should be usable on my Kobo. So COPS's main advantages are : * No need for many dependencies. * No need for a lot of CPU or RAM. * Not much code. * Search is available. * With Dropbox / owncloud it's very easy to have an up to date OPDS server. * It was fun to code. If you want to use the OPDS feed don't forget to specify /feed at the end of your URL.

## Overview
* **Category:** Security, Media, Development
* **Default Port:** `80` (Internal: `80`)
* **Architectures:** amd64, arm64
* **Author / Project:** technorabilia/portainer-templates
* **Source:** [https://github.com/technorabilia/portainer-templates/](https://github.com/technorabilia/portainer-templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
