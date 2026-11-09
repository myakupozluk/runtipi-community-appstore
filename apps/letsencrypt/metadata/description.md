# Let's Encrypt

This container sets up an Nginx webserver and reverse proxy with php support and a built-in letsencrypt client that automates free SSL server certificate generation and renewal processes. It also contains fail2ban for intrusion prevention. Before running this container, make sure that the url and subdomains are properly forwarded to this container's host. - Port 443 on the internet side of the router should be forwarded to this container's port 443. - If you need a dynamic dns provider, you can use the free provider duckdns.org where the url will be yoursubdomain.duckdns.org and the subdomains can be www,ftp,cloud - The container detects changes to url and subdomains, revokes existing certs and generates new ones during start. - It also detects changes to the DHLEVEL parameter and replaces the dhparams file. - If you'd like to password protect your sites, you can use htpasswd. Run the following command on your host to generate the htpasswd file docker exec -it letsencrypt htpasswd -c /config/nginx/.htpasswd &lt;username&gt;

## Overview
* **Category:** Security, Network, Development
* **Default Port:** `80` (Internal: `80`)
* **Architectures:** amd64, arm64
* **Author / Project:** SelfhostedPro/selfhosted_templates
* **Source:** [https://github.com/SelfhostedPro/selfhosted_templates/](https://github.com/SelfhostedPro/selfhosted_templates/)

## Features & Configuration
This application is packaged for Runtipi with Dynamic Compose (Schema Version 2).
Data is persistently stored in your Runtipi storage path (`${APP_DATA_DIR}`).
You can expose this application through your custom domain via Runtipi's Traefik reverse proxy.
