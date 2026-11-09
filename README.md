<div align="center">

# 🚀 Runtipi Community Mega App Store
### 800+ Self-Hosted Applications for Runtipi

[![Apps Count](https://img.shields.io/badge/Apps-833+-brightgreen?style=for-the-badge&logo=docker)](https://github.com)
[![Runtipi](https://img.shields.io/badge/Runtipi-v4.0%2B-blue?style=for-the-badge&logo=linux)](https://runtipi.io)
[![Dynamic Compose](https://img.shields.io/badge/Schema-v2-orange?style=for-the-badge)](https://runtipi.io)
[![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)](LICENSE)

**En geniş ve hafif Runtipi Custom App Store deposu!**  
*The largest and most lightweight community app store for Runtipi home servers.*

</div>

---

## 🇹🇷 Türkçe Açıklama

Bu depo, [Runtipi](https://runtipi.io) sunucunuz için **833+** popüler açık kaynaklı self-hosted uygulamayı barındıran devasa ve hafif bir özel uygulama mağazasıdır.

### 🌟 Özellikler
* **800+ Uygulama Havuzu:** Medya sunucularından güvenlik araçlarına, geliştirici yazılımlarından ev otomasyonuna kadar her şey tek bir depoda.
* **Sıfır Depolama İsrafı (Zero Bloat):** Yalnızca Runtipi mağazasında "Yükle" butonuna bastığınız uygulamaların Docker imajları indirilir. Kullanmadığınız uygulamalar sisteminizde kesinlikle yer kaplamaz.
* **Runtipi Dynamic Compose (Schema v2):** Modern Traefik ters vekil (reverse-proxy), dinamik port yönetimi ve kalıcı veri dizinleri (`${APP_DATA_DIR}`) ile tam uyumludur.
* **Tüm Mimariler Desteklenir:** `amd64` (x86_64) ve `arm64` (Raspberry Pi 4/5 vb.) desteği.

### 📥 Runtipi'ye Nasıl Eklenir? (3 Adımda Kurulum)
1. Runtipi kontrol panelinize giriş yapın.
2. Sol menüden **Settings (Ayarlar)** ➔ **App Stores (Uygulama Mağazaları)** sekmesine gidin.
3. **"Add App Store"** butonuna tıklayın, mağazaya bir isim verin ve bu GitHub repo adresinizi yapıştırıp kaydedin:
   ```text
   https://github.com/KULLANICI_ADINIZ/runtipi-community-appstore
   ```
4. Artık **App Store** sayfanıza girdiğinizde 800'den fazla yeni uygulama anında listelenecektir!

---

## 🇬🇧 English Description

This repository is a community-driven, dynamic app store for [Runtipi](https://runtipi.io) containing **833+** self-hosted applications.

### 🌟 Key Highlights
* **800+ One-Click Deployments:** Media, Productivity, Security, Utilities, Databases, Monitoring, and more.
* **Lightweight & Efficient:** Docker images are only pulled on demand upon installation. Zero background disk consumption.
* **Native Dynamic Compose v2:** Seamless routing with Traefik, managed ports, and persistent volumes under `${APP_DATA_DIR}`.

---

## 📊 Kategori İstatistikleri / Category Statistics

| Kategori / Category | Uygulama Sayısı / App Count |
| :--- | :--- |
| **Development** | 503 |
| **Data** | 237 |
| **Productivity** | 206 |
| **Media** | 173 |
| **Games** | 153 |
| **Network** | 108 |
| **Security** | 97 |
| **Monitoring** | 76 |
| **Utilities** | 64 |
| **Social** | 60 |
| **Automation** | 34 |
| **Finance** | 21 |

---

## 📚 Uygulama Listesi / Application Catalog (833 Apps)

<details>
<summary><b>🔍 Tüm Uygulamaları Görmek İçin Tıklayın / Click to expand full catalog (833 apps)</b></summary>

| Uygulama / App | ID | Kategoriler / Categories | Port | Açıklama / Description |
| :--- | :--- | :--- | :--- | :--- |
| **2FAuth** | `2fauth` | security, development | `8080` | Web app for your two-factor authentication codes, a self-hosted stand-in for Google Authenticator: add accounts by scanning or uploading their QR code... |
| **Activepieces** | `activepieces` | automation | `38080` | Automate your marketing, sales and operations |
| **Actual** | `actual` | security, finance | `5007` | Actual is a super fast privacy-focused app for managing your finances. |
| **Adguard** | `adguard` | network, development | `53` | AdGuard Home is a network-wide software for blocking ads & tracking. After you set it up, it’ll cover ALL your home devices, and you don’t need any cl... |
| **Adguard Home (stack)** | `adguardhome` | network, development | `53` | AdGuard Home is a network-wide software for blocking ads & tracking. After you set it up, it’ll cover ALL your home devices, and you don’t need any cl... |
| **Adguardhome-sync** | `adguardhome-sync` | security, network, development | `8080` | [Adguardhome-sync](https://github.com/bakito/adguardhome-sync/) is a tool to synchronize AdGuardHome config to replica instances. |
| **AFFiNE** | `affine` | development, productivity, data | `8080` | Workspace that mixes docs, whiteboards and databases, so a page can flip between writing and an endless canvas. Edits sync to this server as you type.... |
| **Agent Box** | `agent-box` | security, development | `5000` | Remote AI coding agents on Miget: a persistent box with Claude Code, opencode and Kilo CLI preinstalled, reachable from any browser as a web terminal ... |
| **AI Marketplace Monitor** | `ai-marketplace-monitor` | media, development, productivity | `8467` | Watch Facebook Marketplace for the items you want, rate each new listing with AI, and get notified of good deals. Source: https://github.com/BoPeng/ai... |
| **Airsonic (container)** | `airsonic` | media | `4040` | Airsonic is a free, web-based media streamer, providing ubiqutious access to your music. Use it to share your music with friends, or to listen to your... |
| **Airsonic-advanced** | `airsonic-advanced` | media, development, games | `4040` | [Airsonic-advanced](https://github.com/kagemomiji/airsonic-advanced) is a free, web-based media streamer, providing ubiquitious access to your music. ... |
| **Aldine** | `aldine` | development, productivity | `9993` | Collaborative LaTeX editor you host yourself, an alternative to Overleaf. Real-time editing, a git repository per project, and a sandboxed TeX Live co... |
| **Alpine Xfce4 noVNC** | `alpine-xfce4-novnc` | utilities | `6080` | Alpine xfce4 novnc |
| **Altus** | `altus` | development, social | `3000` | [Altus](https://github.com/amanharwara/altus) is an Electron-based WhatsApp client with themes and multiple account support. |
| **Anchor** | `anchor` | productivity | `3000` | An offline first, self hostable note taking application |
| **Ansible-semaphore** | `ansible-semaphore` | development | `3000` | Modern UI for Ansible |
| **AnythingLLM** | `anythingllm` | media, development, productivity | `8080` | Private ChatGPT-style workspace for your own documents: upload files or scrape web pages, then chat with them using whichever model you like, from Ope... |
| **Anyviz Cloud Adaptor** | `anyviz-cloud-adaptor` | development, data | `9993` | The cloud adapter connects local devices via OPC-UA, Modbus, Siemens, Beckhoff ADS, EtherNet/IP, M-Bus and BACnet to the AnyViz Cloud. |
| **Apache Answer** | `apache-answer` | development, productivity, social | `9080` | Question-and-answer site for a community, product forum or team knowledge base, with voting, accepted answers, tags, reputation and badges. Source: ht... |
| **Apache Httpd** | `apache-httpd` | network, development, games | `8080` | The Apache HTTP Server is a free and open-source cross-platform web server software, released under the terms of Apache License 2.0. Apache is develop... |
| **Apache Kafka** | `kafka` | media, productivity, social | `9092` | 3-node Apache Kafka cluster in KRaft mode (no ZooKeeper) with Kafbat UI, deployable locally with plain Docker Compose or to Miget as a compose stack. |
| **Apprise** | `apprise` | utilities | `8080` | Apprise self-hosted application for Runtipi. |
| **Apprise-api (container)** | `apprise-api` | network, development, monitoring | `8000` | [Apprise-api](https://github.com/caronc/apprise-api) Takes advantage of [Apprise](https://github.com/caronc/apprise) through your network with a user-... |
| **Appsmith** | `appsmith` | development, productivity, monitoring | `1810` | Appsmith (www.appsmith.com) is the first open-source low-code tool that helps developers build dashboards and admin panels very quickly. |
| **Appwrite** | `appwrite` | development | `8080` | Appwrite is a self-hosted backend-as-a-service platform that provides developers with all the core APIs required to build any application. |
| **Arcane** | `arcane` | network, productivity | `3552` | A beautiful, intuitive interface for managing your Docker containers, images, networks, and volumes. No terminal required. |
| **ArchiSteamFarm** | `archisteamfarm` | development, games | `1242` | C# application with primary purpose of farming Steam cards from multiple accounts simultaneously. Source: https://github.com/JustArchiNET/ArchiSteamFa... |
| **Archivebox** | `archivebox` | utilities | `8002` | ArchiveBox is a powerful, self-hosted internet archiving solution to collect, save, and view sites you want to preserve offline. |
| **Ardour** | `ardour` | media, development | `3000` | [Ardour](https://ardour.org/) is an open source, collaborative effort of a worldwide team including musicians, programmers, and professional recording... |
| **Aria2 Pro** | `aria2-pro` | productivity, data | `6800` | A perfect Aria2 Docker image. Out of the box, just add download tasks and don't need to think about anything else. |
| **Aria2Pro** | `aria2pro` | utilities | `6800` | Aria2Pro self-hosted application for Runtipi. |
| **AriaNG** | `ariang` | development, data, games | `8080` | AriaNg is a modern web frontend making aria2 easier to use. AriaNg is written in pure html & javascript, thus it does not need any compilers or runtim... |
| **Asciinema {shmolf}** | `asciinema` | development | `9993` | Self-hosted terminal recording and playback |
| **Atrium** | `atrium` | development, productivity, data | `8080` | Client portal for agencies and freelancers. Share project progress, files, tasks and invoices through a branded portal. Source: https://github.com/Vib... |
| **Audacity** | `audacity` | media, development | `3000` | [Audacity](https://www.audacityteam.org/) is an easy-to-use, multi-track audio editor and recorder. Developed by a group of volunteers as open source. |
| **Audiobookshelf** | `audiobookshelf` | media, games | `13378` | Self hosted audiobook and podcast server |
| **AudioMuse-AI** | `audiomuse-ai` | media, development, games | `8080` | Automatic playlist generation for self-hosted music servers. Analyses your library locally to group tracks by how they sound. Works with Navidrome, Je... |
| **AudioMuse-AI (NVIDIA GPU)** | `audiomuse-ai-nvidia` | media, development | `8080` | AudioMuse-AI with NVIDIA GPU acceleration for the analysis and clustering jobs. Needs the NVIDIA Container Toolkit on the host. GitHub: [NeptuneHub/Au... |
| **Audiosilo** | `audiosilo` | media, development, data | `8080` | [AudioSilo](https://audiosilo.app) is a self-hosted audiobook server. Point it at your audiobook folders and listen from the built-in web player or th... |
| **Aurral** | `aurral` | media, development, data | `8080` | Streamlined Artist Request Manager for Lidarr. Search for artists using the MusicBrainz database and seamlessly add them to your Lidarr music library.... |
| **Authelia** | `authelia` | security, games | `9091` | An open-source authentication and authorization server providing 2-factor authentication and single sign-on (SSO) for your applications via a web port... |
| **Authentik** | `authentik` | security, development | `8080` | Authentik is an open-source Identity Provider focused on flexibility and versatility |
| **Autobrr** | `autobrr` | media, data, automation | `7474` | Autobrr is the modern download automation tool for torrents. |
| **Azahar** | `azahar` | development, games | `3000` | [Azahar](https://azahar-emu.org/) is an open-source 3DS emulator based on Citra. |
| **Azure Pipelines Agent** | `azp-agent` | development, productivity | `8080` | A self-hosted Azure Pipelines agent (Azure DevOps), built from Microsoft's official Dockerfile recipe - the agent ships no container image, this is th... |
| **Babybuddy** | `babybuddy` | development, social | `8000` | [Babybuddy](https://github.com/babybuddy/babybuddy) is a buddy for babies! Helps caregivers track sleep, feedings, diaper changes, tummy time and more... |
| **Bagisto** | `bagisto` | utilities | `5000` | Bagisto - the open-source Laravel ecommerce platform: catalog, cart, checkout, multi-channel and multi-currency storefronts, and a full admin. MIT-lic... |
| **Baikal** | `baikal` | media, productivity, games | `8220` | Baïkal is a lightweight CalDAV+CardDAV server. It offers an extensive web interface with easy management of users, address books and calendars. |
| **Bambustudio** | `bambustudio` | development, productivity, data | `3000` | [Bambu Studio](https://bambulab.com/en/download/studio) is an open-source, cutting-edge, feature-rich slicing software. It contains project-based work... |
| **Baserow (container)** | `baserow` | development, data | `80` | Open source no-code database and Airtable alternative |
| **Bazarr (container)** | `bazarr` | media, data | `6767` | [Bazarr](https://www.bazarr.media/) is a companion application to Sonarr and Radarr. It can manage and download subtitles based on your requirements. ... |
| **Beets** | `beets` | media, development, finance | `8337` | [Beets](http://beets.io/) is a music library manager and not, for the most part, a music player. It does include a simple player plugin and an experim... |
| **BentoPDF** | `bentopdf` | development, productivity, data | `8090` | PDF toolkit that runs in your browser, so files never leave your machine. Merge, split, compress, convert, sign and edit. Source: https://github.com/a... |
| **Beszel** | `beszel` | productivity, data, monitoring | `8090` | A lightweight server resource monitoring hub with historical data, docker stats, and alerts. |
| **Bitcoin-knots** | `bitcoin-knots` | finance, games | `3000` | [Bitcoin Knots](https://bitcoinknots.org/) can be used as a desktop client for regular payments or as a full node server utility for merchants and oth... |
| **Bitwarden RS** | `bitwardenrs` | development, games | `80` | This is a Bitwarden server API implementation written in Rust compatible with upstream Bitwarden clients*, perfect for self-hosted deployment where ru... |
| **Blade-of-agony** | `blade-of-agony` | data, games | `3000` | [Wolfenstein: Blade of Agony](https://boa.realm667.com/) is a story-driven WWII shooter inspired by Wolfenstein and Doom. |
| **Blender** | `blender` | games | `3000` | [Blender](https://www.blender.org/) is a free and open-source 3D computer graphics software toolset used for creating animated films, visual effects, ... |
| **Blinko** | `blinko` | development, productivity | `1111` | Blinko is an innovative open-source project designed for individuals who want to quickly capture and organize their fleeting thoughts. Blinko allows u... |
| **Boinc** | `boinc` | development | `8080` | [BOINC](https://boinc.berkeley.edu/) is a platform for high-throughput computing on a large scale (thousands or millions of computers). It can be used... |
| **Booksonic** | `booksonic` | media, games | `4040` | Booksonic is a server and an app for streaming your audiobooks to any pc or android phone. Most of the functionality is also availiable on other platf... |
| **Bookstack (container)** | `bookstack` | media, development, productivity | `6875` | [Bookstack](https://codeberg.org/bookstack/bookstack) is a free and open source Wiki designed for creating beautiful documentation. Featuring a simple... |
| **Bookstack (stack)** | `bookstack-stack` | media, development, productivity | `8080` | Bookstack is a free and open source Wiki designed for creating beautiful documentation. Feautring a simple, but powerful WYSIWYG editor it allows for ... |
| **Bookstack (swarm)** | `bookstack-swarm` | media, development, productivity | `8080` | Bookstack is a free and open source Wiki designed for creating beautiful documentation. Feautring a simple, but powerful WYSIWYG editor it allows for ... |
| **Brave** | `brave` | utilities | `3000` | [The Brave browser](https://brave.com/) is a fast, private and secure web browser for PC, Mac and mobile. |
| **Broadlink Manager** | `broadlink-manager` | development | `8080` | BroadlinkManager is a Flask powerd, easy to use system that hepls you to work with Broadlink Devices. |
| **Budibase** | `budibase` | development, productivity | `8080` | Budibase allows no-code users to build apps quickly, with more functionality available with a little bit of inline code. |
| **Bugsink** | `bugsink` | development, data | `5000` | Bugsink, self-hosted error tracking compatible with the Sentry SDKs, in a single container. The lightest way to own your error data: one app + one man... |
| **Buildkite Agent** | `buildkite-agent` | development | `8080` | A Buildkite agent: Buildkite hosts the UI and orchestration, your agents run the jobs - the hybrid-CI model where compute was always meant to be yours... |
| **Buzz** | `buzz` | security, development, productivity | `5000` | Buzz - a self-hosted workspace where humans and AI agents share the same rooms. Under the hood it is a Nostr relay: every message, reaction, workflow ... |
| **Bytebase** | `bytebase` | development, data | `8080` | Database change management for teams. Plan, review and roll out schema changes to Postgres, MySQL and 20-odd other databases with a full history, or q... |
| **Caddy** | `caddy` | network, games | `80` | Open-source web server with automatic HTTPS written in Go |
| **cairn** | `cairn` | development, monitoring | `8080` | The directory page for the people you host services for: no account, multilingual, live status, one tiny container. Source: https://github.com/MorganK... |
| **Cal.com** | `calcom` | media, productivity, data | `5000` | Cal.com - open-source scheduling: personal and team booking pages, availability rules, round-robin and collective events, workflows and reminders, and... |
| **Calibre** | `calibre` | media | `8080` | [Calibre](https://calibre-ebook.com/) is a powerful and easy to use e-book manager. Users say it's outstanding and a must-have. It'll allow you to do ... |
| **Calibre-web** | `calibre-web` | media, development, data | `8083` | [Calibre-web](https://github.com/janeczku/calibre-web) is a web app providing a clean interface for browsing, reading and downloading eBooks using an ... |
| **Calligra** | `calligra` | development, productivity, data | `3000` | [Calligra](https://calligra.org/) is an office and graphic art suite by KDE. It is available for desktop PCs, tablet computers, and smartphones. It co... |
| **Campfire** | `campfire` | social | `5000` | Campfire - 37signals' free, open-source group chat: rooms, direct messages, file sharing, full-text search, @mentions, sounds, and Web Push. It was th... |
| **Cantinarr** | `cantinarr` | security, media, development | `8585` | Media requests and server management in one app. Household members browse and request movies, shows, books, and music, follow downloads, and get notif... |
| **Cardigann** | `cardigann` | media, data, monitoring | `5060` | Cardigann, a server for adding extra indexers to Sonarr, SickRage and CouchPotato via Torznab and TorrentPotato proxies. Behind the scenes Cardigann l... |
| **Casdoor** | `casdoor` | security, development, social | `8080` | Identity and single sign-on server, so your other apps can share one login over OAuth 2, OIDC, SAML or CAS, with a web UI for users, organisations, ap... |
| **CashPilot** | `cashpilot` | development, data, monitoring | `8080` | Self-hosted passive income orchestrator for bandwidth sharing, DePIN, storage, and GPU compute services. Source: https://github.com/GeiserX/CashPilot |
| **Castopod** | `castopod` | media | `8080` | Castopod is a free and open-source hosting platform made for podcasters. |
| **Change Detection** | `changedetection` | network, development, monitoring | `8080` | Self-hosted website change detection monitoring. Source: https://github.com/dgtlmoon/changedetection.io |
| **Changedetection.io (container)** | `changedetection-io` | development, automation, monitoring | `5000` | [Changedetection.io](https://github.com/dgtlmoon/changedetection.io) provides free, open-source web page monitoring, notification and change detection... |
| **Chatwoot** | `chatwoot` | development, productivity, automation | `5000` | Chatwoot - open-source customer support: shared team inbox, website live-chat widget, email and social channels, help center, and automations. This te... |
| **CheckCle** | `checkcle` | development, monitoring, games | `8090` | Open Source solution for seamless, real-time monitoring of full-stack systems, applications, and infrastructure. Provides deep insights across servers... |
| **Checkmate** | `checkmate` | network, monitoring | `5000` | An open source uptime and infrastructure monitoring application. |
| **Chevereto** | `chevereto` | media | `80` | Chevereto is a powerful and fast image hosting script that allows you to create your very own full featured image hosting website in just minutes. Ple... |
| **Chibisafe** | `chibisafe` | development | `2425` | Chibisafe is a modern and self-hosted take on file uploading services that can handle anything you throw at it thanks to it's robust and fast API, chu... |
| **Chiefonboarding** | `chiefonboarding` | monitoring | `127` | ChiefOnboarding is a free and open source employee onboarding platform. You can onboarding new hires through Slack or the dashboard. |
| **Chowdown** | `chowdown` | development | `4000` | Have recipes in seconds with plain text formatting and create beatiful recipe pages with automated ease. |
| **ChromaDB** | `chromadb` | security, network, development | `8000` | Chroma vector database, single container + volume, internal-only (Chroma has no built-in auth; the project network is the boundary, like the MongoDB t... |
| **Chrome** | `chrome` | development | `3000` | [Chrome](https://www.google.com/chrome/) is the official web browser from Google, built to be fast, secure, and customizable. |
| **Chromium** | `chromium` | productivity | `3000` | [Chromium](https://www.chromium.org/chromium-projects/) is an open-source browser project that aims to build a safer, faster, and more stable way for ... |
| **Chrony NTP** | `chrony-ntp` | network, development, data | `123` | chrony is a versatile implementation of the Network Time Protocol (NTP). It can synchronise the system clock with NTP servers, reference clocks (e.g. ... |
| **Clamav** | `clamav` | media, development | `3310` | ClamAV® is an open source antivirus engine for detecting trojans, viruses, malware & other malicious threats. |
| **ClickHouse Cluster** | `clickhouse` | development, data | `8123` | 3-node ClickHouse cluster, one shard, three replicas, with embedded ClickHouse Keeper (no separate ZooKeeper pods). Internal-only; 20 GB per node. |
| **Cloud Commander** | `cloudcmd` | development, productivity, data | `8000` | Cloud Commander a file manager for the web with console and editor. |
| **CloudBeaver** | `cloudbeaver` | development, data | `8978` | Cloud database manager providing a web interface for working with various databases. Source: https://github.com/dbeaver/cloudbeaver |
| **Cloudflare DDNS** | `cloudflare-ddns` | security, network, development | `8080` | A robust Cloudflare DDNS updater with a small footprint. The program will detect your machine's public IP addresses and update DNS records using the C... |
| **Cloudflared-web** | `cloudflared-web` | network, development, productivity | `8080` | A docker image that packages both cloudflared cli and a simple Web UI to easily start or stop remotely-managed Cloudflare tunnel. Source: https://gith... |
| **Cloudreve** | `cloudreve` | media, development, productivity | `5212` | Cloud drive for your own files, with share links, WebDAV, previews for documents, photos and video, and offline downloads. Source: https://github.com/... |
| **Cockpit {shmolf}** | `cockpit-cms` | development | `8088` | Cockpit is a headless CMS with an API-first approach that puts content first. |
| **CockroachDB (container)** | `cockroachdb-container` | development, data | `26257` | An open-source, survivable, strongly consistent, scale-out SQL database |
| **CockroachDB (stack)** | `cockroachdb-stack` | utilities | `8080` | CockroachDB cluster |
| **CockroachDB (swarm)** | `cockroachdb-swarm` | development, data | `8080` | CockroachDB cluster |
| **Code-server (container)** | `code-server` | media, development, data | `8443` | [Code-server](https://coder.com) is VS Code running on a remote server, accessible through the browser. - Code on your Chromebook, tablet, and laptop ... |
| **Codex** | `codex` | media, development, games | `9810` | Codex is a web server comic book browser and reader. |
| **Codiad** | `codiad` | development, productivity | `80` | Codiad is a web-based IDE framework with a small footprint and minimal requirements. |
| **Cognee** | `cognee` | productivity, data, social | `5000` | Cognee - the memory engine for AI agents: ingest documents, chats, and data; cognify them into a knowledge graph + vector index; query the result as l... |
| **CommaFeed** | `commafeed` | development, productivity, social | `8082` | RSS reader in the style of Google Reader, with four layouts, keyboard shortcuts for nearly everything, rules that mark entries as read, OPML import an... |
| **CommandBox** | `commandbox` | development | `8080` | ColdFusion (CFML) CLI |
| **ContentBox** | `contentbox` | utilities | `8080` | Open-source modular CMS |
| **ConvertX** | `convertx` | media, development, productivity | `3000` | File converter for over a thousand formats, covering images, documents, audio, video and ebooks. Source: https://github.com/C4illin/ConvertX |
| **Convex** | `convex` | development, data, monitoring | `3210` | Convex backend-as-a-service, self-hosted: reactive database + functions + scheduler, with the dashboard. SQLite state on a volume; the open-source bac... |
| **Cops** | `cops` | security, media, development | `80` | [Cops](https://github.com/mikespub-org/seblucas-cops) by Sébastien Lucas, now maintained by MikesPub, stands for Calibre OPDS (and HTML) Php Server. C... |
| **copyparty** | `copyparty` | media, development, data | `8080` | File server in one Python app, with resumable uploads, thumbnails, search and a music player in the browser, plus WebDAV for mounting it as a drive. S... |
| **CouchPotato** | `couchpotato` | media, development, data | `5050` | CouchPotato (CP) is an automatic NZB and torrent downloader. You can keep a "movies I want"-list and it will search for NZBs/torrents of these movies ... |
| **Craft-apps** | `craft-apps` | media, development | `3000` | [ArtCraft](https://getartcraft.com/) is a suite of open source creative applications written in Rust. This image bundles PhotoCraft (image editor), Ve... |
| **CrateDB** | `cratedb` | development, data | `4200` | An open-source distributed SQL database |
| **Cronicle** | `cronicle` | data, automation, monitoring | `5000` | Cronicle, a cron replacement with a web UI: schedules, run history, chaining, retries, and alerts. Single container, two small volumes (job data + log... |
| **Crowdsec WEB UI** | `crowdsec-web-ui` | security, development, monitoring | `8080` | A modern, responsive web interface for managing CrowdSec alerts and decisions. Built with React, Vite, Bun, and Tailwind CSS. |
| **Cryptofolio** | `cryptofolio` | finance, monitoring | `7280` | Cryptofolio is an open-source, and self-hosted solution for tracking your cryptocurrency holdings. It features a web interface, an Android mobile app,... |
| **CryptPad** | `cryptpad` | development, productivity, data | `3000` | Collaboration suite, encrypted and open-source. Source: https://github.com/cryptpad/cryptpad |
| **Cura** | `cura` | development | `3000` | [UltiMaker Cura](https://ultimaker.com/software/ultimaker-cura/) is free, easy-to-use 3D printing software trusted by millions of users. Fine-tune you... |
| **CyberChef** | `cyberchef` | security, development, data | `8088` | Web app for encoding, decoding, encrypting, compressing and picking apart data, by chaining hundreds of small operations into a recipe. Source: https:... |
| **Daapd** | `daapd` | media, development, games | `8080` | DAAP (iTunes) media server with support for AirPlay devices, Apple Remote (and compatibles), MPD and internet radio. |
| **Dagu** | `dagu` | development, data, automation | `8080` | A powerful, self-contained DAG-based job scheduler with a web UI, YAML definitions, and no dependencies. Source: https://github.com/dagucloud/dagu |
| **Darktable** | `darktable` | media, development, data | `3000` | [darktable](https://www.darktable.org/) is an open source photography workflow application and raw developer. A virtual lighttable and darkroom for ph... |
| **Dashdot** | `dashdot` | monitoring, games | `9980` | Dashdot is a modern server dashboard, running on the latest tech, designed with glassmorphism in mind. It is intended to be used for smaller VPS and p... |
| **DashMachine** | `dashmachine` | media, monitoring | `5000` | Another application bookmark , with fun features. |
| **Dashy (container)** | `dashy` | security, development, monitoring | `4000` | The ultimate personal dashboard, keep all your self-hosted services and websites organized. Includes live status monitoring, widgets, icons, themes, 3... |
| **Databag** | `databag` | development, data, social | `7000` | A lightweight federated messaging service. Source: https://github.com/balzack/databag |
| **Datadog agent (container)** | `datadog-agent-container` | data, monitoring | `8080` | Collect events and metrics |
| **Datadog agent (swarm)** | `datadog-agent-swarm` | data, monitoring | `8080` | Collect events and metrics |
| **DaVinci Postgres Server** | `davinci-postgres-server` | development, games | `5432` | DaVinci Resolve Postgresql Server, Davinci requires a specific version of postgres db, this container will install the version needed |
| **Davos** | `davos` | development, data, automation | `8080` | [Davos](https://github.com/linuxserver/davos) is an FTP automation tool that periodically scans given host locations for new files. It can be configur... |
| **Dawarich** | `dawarich` | security | `8080` | Self-Hosted Location History Tracker. - Visualize your location history, track your movements, and analyze your travel patterns with complete privacy ... |
| **DbGate** | `dbgate` | development, data, games | `8080` | Database manager in the browser for PostgreSQL, MySQL, MariaDB, SQL Server, SQLite, MongoDB, Redis and more: browse and edit tables, write queries, co... |
| **Ddclient** | `ddclient` | security, network, development | `80` | [Ddclient](https://github.com/ddclient/ddclient) is a Perl client used to update dynamic DNS entries for accounts on Dynamic DNS Network Service Provi... |
| **DeeMix** | `deemix` | media, data | `6595` | Deemix is a deezer downloader built from the ashes of Deezloader Remix. |
| **Deluge** | `deluge` | data | `8112` | [Deluge](http://deluge-torrent.org/) is a lightweight, Free Software, cross-platform BitTorrent client. * Full Encryption * WebUI * Plugin System * Mu... |
| **Deluge openvpn** | `deluge-openvpn` | security, network, development | `8112` | This container contains OpenVPN and Deluge with a configuration where Deluge is running only when OpenVPN has an active tunnel. It bundles configurati... |
| **Deployable Sh** | `deployable-sh` | utilities | `5000` | Deployable Sh self-hosted application for Runtipi. |
| **Dify** | `dify` | social | `8080` | Dify - the LLM application platform: a visual builder for chatbots, agents, and workflows, with built-in RAG, model management, and observability. |
| **Digikam** | `digikam` | media | `3000` | [digiKam](https://www.digikam.org/): Professional Photo Management with the Power of Open Source |
| **Directus** | `directus` | development, data, finance | `5000` | Directus 11 - an instant headless CMS and REST/GraphQL API over Postgres, with a data studio your editors will actually enjoy. One app container + a m... |
| **Diskover (container)** | `diskover` | development, data, monitoring | `80` | [Diskover](https://github.com/diskoverdata/diskover-community) is an open source file system indexer that uses Elasticsearch to index and manage data ... |
| **Docker Compose maker** | `dockercomposemaker` | productivity, data | `7576` | DCM (Docker Compose Maker) is a simple yet powerful tool that helps you create docker-compose.yaml files for your self-hosted applications. |
| **Docker Container Stats** | `docker-container-stats` | productivity | `8383` | Docker Container Stats is a web interface for viewing historical and current statistics per docker container (cpu, mem, net i/o, block i/o) - in a doc... |
| **Docker Registry** | `docker-registry` | security, development, productivity | `5000` | Your own private container registry - the CNCF Distribution registry (the same engine behind Docker Hub) - with https, basic-auth, and image storage o... |
| **Dockge** | `dockge` | productivity | `5001` | A fancy, easy-to-use and reactive self-hosted docker compose.yaml stack-oriented manager. |
| **DockRoute** | `dockroute` | security, network, development | `8080` | External-DNS for plain Docker hosts: watches running containers, reads dockroute.* labels and reconciles the matching DNS records — and Cloudflare Tun... |
| **Docmost** | `docmost` | development, productivity | `3000` | Open source collaborative wiki and documentation software, an alternative to Confluence and Notion. Source: https://github.com/docmost/docmost |
| **Documenso** | `documenso` | security, development, productivity | `5000` | Documenso - the open-source DocuSign alternative: signing workflows, templates, teams, and an API, with real PKCS#12 document sealing. One app contain... |
| **Documize** | `documize` | productivity | `5432` | Documize Community is an open source, modern, self-hosted, enterprise-grade knowledge management solution. |
| **DocuSeal (container)** | `docuseal` | development, productivity | `3000` | Open source DocuSign alternative for document filling and signing. Source: https://github.com/docusealco/docuseal |
| **Dogwalk** | `dogwalk` | productivity, games | `3000` | [DOGWALK](https://studio.blender.org/projects/dogwalk/) is Blender Studio's long awaited second game project, focused on creating a bite-sized interac... |
| **Dokemon** | `dokemon` | data, monitoring | `9090` | Deploy compose files, start/stop containers, delete unused images, view logs |
| **Dokku (container)** | `dokku-container` | utilities | `22` | Dokku setup as a container |
| **Dokku (stack)** | `dokku-stack` | utilities | `9993` | Dokku setup as a compose file |
| **Dokuwiki** | `dokuwiki` | security, development, productivity | `80` | [Dokuwiki](https://www.dokuwiki.org/dokuwiki/) is a simple to use and highly versatile Open Source wiki software that doesn't require a database. It i... |
| **Dolibarr** | `dolibarr` | development, productivity, finance | `8080` | ERP and CRM for small businesses and freelancers: contacts, quotes, orders, invoices and payments, stock, projects, expense reports, HR and accounting... |
| **Dolphin** | `dolphin` | games | `3000` | [Dolphin Emulator](https://dolphin-emu.org/) lets you play GameCube and Wii games with various graphical enhancements and other features are available... |
| **Domoticz** | `domoticz` | development, automation, monitoring | `1443` | Domoticz is a Home Automation System that lets you monitor and configure various devices like: Lights, Switches, various sensors/meters like Temperatu... |
| **Donetick** | `donetick` | development, productivity, automation | `2021` | Chore and task tracker for households, with natural-language scheduling, assignee rotation, subtasks, points and rewards, labels, NFC tags and a calen... |
| **Doplarr_rs** | `doplarr-rs` | media, development | `80` | [Doplarr_rs](https://github.com/activexray/doplarr_rs) is a Discord bot for requesting media through *arr backends, written in Rust. |
| **Dosbox-staging** | `dosbox-staging` | media, development, games | `3000` | [DOSBox Staging](https://www.dosbox-staging.org/) is a modern continuation of DOSBox a free and open-source emulator that enables the execution of MS-... |
| **Doublecommander** | `doublecommander` | development, data | `3000` | [Double Commander](https://doublecmd.sourceforge.io/) is a free cross platform open source file manager with two panels side by side. It is inspired b... |
| **Dozzle** | `dozzle` | productivity, data, monitoring | `8888` | Dozzle is a small lightweight application with a web based interface to monitor Docker logs. It doesn’t store any log files. It is for live monitoring... |
| **Dradis** | `dradis` | security | `3000` | Dradis Framework: Collaboration and reporting for IT Security teams http://dradisframework.org |
| **Draw.io** | `drawio` | network, development, productivity | `28181` | draw.io (formerly Diagramly) is free online diagram software. You can use it as a flowchart maker, network diagram software, to create UML online, as ... |
| **drawDB** | `drawdb` | development, data, games | `8098` | Database diagram editor for drawing entity relationships in the browser, then exporting them as SQL for MySQL, PostgreSQL, SQLite, MariaDB or SQL Serv... |
| **Droppy** | `droppy` | data, games | `8989` | Droppy is a self-hosted file storage server |
| **Drupal** | `drupal` | utilities | `80` | Open-source content management framework |
| **Duckdns** | `duckdns` | security, network, social | `80` | [Duckdns](https://duckdns.org/) is a free service which will point a DNS (sub domains of duckdns.org) to an IP of your choice. The service is complete... |
| **Duckstation** | `duckstation` | games | `3000` | [DuckStation](https://duckstation.org/) is a PS1 Emulator aiming for the best accuracy and game support. |
| **Duplicacy** | `duplicacy` | development, data | `3875` | Duplicacy backs up your files to many cloud storages with client-side encryption and the highest level of deduplication |
| **Duplicati** | `duplicati` | data, games | `8200` | [Duplicati](https://www.duplicati.com/) is a backup client that securely stores encrypted, incremental, compressed backups on local storage, cloud sto... |
| **Easy!Appointments** | `easy-appointments` | media, development, productivity | `8080` | Online booking site for appointments: customers pick a service, a provider and a free slot, and you manage it all from a calendar with working hours, ... |
| **Eclipse Mosquitto MQTT** | `eclipse-mosquitto` | development, automation, games | `1883` | Eclipse Mosquitto is an open source message broker that implements the MQTT protocol versions 5.0, 3.1.1 and 3.1. Mosquitto is lightweight and is suit... |
| **Eden** | `eden` | development, games | `3000` | [Eden](https://eden-emu.dev/) is an experimental open-source emulator for the Nintendo Switch, built with performance and stability in mind. |
| **Elasticsearch** | `elasticsearch` | development, data | `9200` | Open-source search and analytics engine |
| **Emby** | `emby` | media, development, games | `8096` | [Emby](https://emby.media/) organizes video, music, live TV, and photos from personal media libraries and streams them to smart TVs, streaming boxes a... |
| **EmbyStat** | `embystat` | media, games | `6555` | Embystat is a personal web server that can calculate all kinds of statistics from your (local) Emby server. Just install this on your server and let h... |
| **EMQX Open Source MQTT Broker** | `emqx-open-source-mqtt-broker` | automation | `9993` | Open-source MQTT broker for IoT, IIoT, and connected vehicles - Single Broker deployment |
| **EspoCRM** | `espocrm` | development, productivity | `8080` | CRM for keeping track of customers and sales: accounts, contacts, leads, opportunities, cases, meetings and calls, with a shared calendar, email inbox... |
| **Etherpad** | `etherpad` | development, productivity, social | `8080` | Collaborative text editor where everyone types in the same document at once, with history, chat and plugins. This one runs on Postgres. Source: https:... |
| **Eufy Security WS** | `eufy-security-ws` | security | `3993` | Eufy Security Web Socket. Edit container and add username & password. |
| **Excalidraw** | `excalidraw` | productivity | `3111` | Virtual whiteboard for sketching hand-drawn like diagrams. Collaborative and end-to-end encrypted. |
| **ezBookkeeping** | `ezbookkeeping` | media, development, data | `8080` | Personal finance app for logging what you spend and earn across accounts and currencies, with receipt photos, scheduled transactions and charts. Impor... |
| **Facebox** | `facebox` | utilities | `1080` | Facebox self-hosted application for Runtipi. |
| **Factorio Server** | `factorio` | automation, games | `34197` | Headless Factorio via factoriotools/factorio - the community-standard image. Saves, mods, and server settings live on the `/factorio` volume; a new ma... |
| **Fail2ban** | `fail2ban` | security, network | `80` | [Fail2ban](http://www.fail2ban.org/) is a daemon to ban hosts that cause multiple authentication errors. |
| **Faster-whisper** | `faster-whisper` | development, games | `10300` | [Faster-whisper](https://github.com/SYSTRAN/faster-whisper) is a reimplementation of OpenAI's Whisper model using CTranslate2, which is a fast inferen... |
| **FDO** | `fdo` | utilities | `8080` | FDO |
| **Feedcord** | `feedcord` | social, games | `8080` | FeedCord is a dead-simple RSS Reader designed to integrate seamlessly with Discord. With just a few configuration steps, you can have a news feed text... |
| **Fenrus** | `fenrus` | monitoring | `3003` | Fenrus is a Node application and requires NodeJS to run. Once NodeJS is installed you can run Fenrus |
| **Ferdi Server** | `ferdi-server` | social, games | `3333` | Ferdi is a messaging browser that allows you to combine your favourite messaging services into one application |
| **Ferdiserver** | `ferdiserver` | games | `3333` | Ferdiserver self-hosted application for Runtipi. |
| **Ferdium (container)** | `ferdium` | development, social | `3000` | [Ferdium](https://ferdium.org/) is a desktop app that helps you organize how you use your favourite apps by combining them into one application. |
| **Ferret** | `ferret` | media, development, productivity | `8787` | Self-hosted home inventory: find anything you own. Photos, barcodes, QR labels, warranties, maintenance and an insurance report, with a REST API, an M... |
| **Ffmpeg** | `ffmpeg` | media, development, productivity | `80` | # This container needs special attention. Please check https://hub.docker.com/r/linuxserver/ffmpeg for details. |
| **File browser (container)** | `file-browser-container` | data | `80` | A web file manager |
| **FileBrowser (stack)** | `filebrowser` | data | `5000` | FileBrowser - a fast web UI over a file volume: upload, organize, preview, edit, and share files via public links, with per-user scopes. Apache-2.0, n... |
| **FileBrowser latest** | `filebrowser-latest` | utilities | `8082` | Web File Browser which can be used as a middleware or standalone app. |
| **Filegator** | `filegator` | data | `8886` | FileGator is a free, open-source, self-hosted web application for managing files and folders. |
| **Filepizza** | `filepizza` | data | `3333` | Peer-to-peer file transfers in your browser |
| **Filerun** | `filerun` | media, development, productivity | `9993` | access your files anywhere through self-hosted secure cloud storage, file backup and sharing for your photos, videos, files and more. |
| **Filestash** | `filestash` | data | `8080` | A Dropbox-like file manager that let you manage your data anywhere it is located. |
| **Filezilla** | `filezilla` | productivity | `3000` | [FIleZilla](https://filezilla-project.org/) Client is a fast and reliable cross-platform FTP, FTPS and SFTP client with lots of useful features and an... |
| **Firefly III** | `firefly-iii` | development, finance | `8080` | Personal finance manager for tracking what comes in and goes out, with budgets, subscriptions, recurring transactions, rules and reports. This one run... |
| **Firefox (container)** | `firefox` | development | `3000` | [Firefox](https://www.mozilla.org/en-US/firefox/) Browser, also known as Mozilla Firefox or simply Firefox, is a free and open-source web browser deve... |
| **Fireshare** | `fireshare` | media, development | `8888` | Fireshare: Share your game clips, videos, or other media via unique links. |
| **Fizzy** | `fizzy` | development, productivity | `5000` | Fizzy - 37signals' free, open-source kanban: fast, focused boards for bugs, issues, ideas, and small projects. |
| **Flagsmith** | `flagsmith` | development | `8080` | Feature flags and remote config for your apps: switch features on per environment, roll out to a percentage or a segment of users, and change values w... |
| **Flame** | `flame` | development, games | `5005` | Flame is self-hosted startpage for your server. Its design is inspired (heavily) by SUI. Flame is very easy to setup and use. With built-in editors, i... |
| **Flame-Dashboard** | `flame-dashboard` | development, monitoring, games | `5005` | Flame is self-hosted startpage for your server. Its design is inspired (heavily) by SUI. Flame is very easy to setup and use. With built-in editors, i... |
| **FlareSolverr** | `flaresolverr` | network, data, games | `8191` | FlareSolverr is a proxy server to bypass Cloudflare and DDoS-GUARD protection. |
| **flatnotes** | `flatnotes` | development, productivity, data | `8080` | Distraction-free notes app with no folders or database, just a folder of markdown files behind full-text search, tags, wikilinks and a raw or WYSIWYG ... |
| **Flexget** | `flexget` | media, data, automation | `5050` | [Flexget](http://flexget.com/) is a multipurpose automation tool for all of your media. |
| **Floating License Server** | `floating-license-server` | games | `6200` | License Server for Softing edgeConnector products |
| **Flood** | `flood` | security, productivity, data | `8282` | A docker image with qBittorrent and the Flood UI, also optional WireGuard VPN support. |
| **Flowise** | `flowise` | development, social | `5000` | Flowise - the visual builder for LLM apps: drag-and-drop chatflows and agentflows over 100+ integrations (models, vector stores, tools), with APIs and... |
| **Flowiseai** | `flowiseai` | utilities | `8459` | Open source UI visual tool to build your customized LLM flow using LangchainJS, written in Node Typescript/Javascript |
| **FluxDown** | `fluxdown` | development, data | `17800` | Multi-protocol download manager with a web UI. Handles HTTP/HTTPS, FTP, BitTorrent (DHT/magnet), eD2K/Kad, HLS and DASH, with dynamic file segmentatio... |
| **Flycast** | `flycast` | development, games | `3000` | [Flycast](https://github.com/flyinghead/flycast) is a multi-platform Sega Dreamcast, Naomi, Naomi 2, and Atomiswave emulator derived from reicast. |
| **Foldingathome** | `foldingathome` | development, productivity, data | `80` | [Folding@home](https://foldingathome.org/) is a distributed computing project for simulating protein dynamics, including the process of protein foldin... |
| **Forgejo (container)** | `forgejo` | development | `3000` | A self-hosted lightweight software forge, providing Git hosting, code review, issue tracking, and CI/CD. Source: https://codeberg.org/forgejo/forgejo |
| **Forgejo Runner** | `forgejo-runner` | development, productivity | `8080` | A Forgejo Actions runner in `host` mode - CI for your self-hosted Forgejo or for Codeberg, with jobs running as shell steps in this container (no Dock... |
| **FoundryVTT Server** | `foundryvtt` | development, productivity, games | `30000` | This docker image provides the FoundryVTT system for hosting your own virtual table top games. |
| **Freeboard** | `freeboard` | development, data, automation | `8000` | Freeboard is a turn-key HTML-based 'engine' for dashboards. Besides a nice looking layout engine, it provides a plugin architecture for creating datas... |
| **Freecad** | `freecad` | development | `3000` | [FreeCAD](https://www.freecad.org/) is a general-purpose parametric 3D computer-aided design (CAD) modeler and a building information modeling (BIM) s... |
| **Freescout** | `freescout` | utilities | `8080` | FreeScout is the super lightweight free open source help desk and shared inbox written in PHP (Laravel framework) – self hosted clone of HelpScout. |
| **Freshrss** | `freshrss` | social | `80` | [Freshrss](https://freshrss.org/) is a free, self-hostable aggregator for rss feeds. |
| **Frigate NVR** | `frigatenvr` | media, development | `1935` | A complete and local NVR designed for Home Assistant with AI object detection. Uses OpenCV and Tensorflow to perform realtime object detection locally... |
| **Funkwhale** | `funkwhale` | media, network, development | `5000` | A social platform to enjoy and share music.Funkwhale is a community-driven project that lets you listen and share music and audio within a decentraliz... |
| **Fusion** | `fusion` | social | `8980` | A lightweight RSS feed aggregator and reader. |
| **Fuuz Device Gateway** | `fuuz-device-gateway` | network, development, data | `5500` | A secure gateway that connects on-premise devices, PLCs, and data sources to the Fuuz Cloud for seamless, real-time integration. |
| **Gaps** | `gaps` | media, games | `8484` | Gaps searches through your Plex Server or local folders for all movies, then queries for known movies in the same collection. |
| **Garage** | `garage` | data | `3900` | Garage - the S3-compatible object store the self-hosting community moved to after MinIO archived its open source in 2026: a single static Rust binary,... |
| **Gathio** | `gathio` | security, development, social | `3022` | Gathio is a simple, federated, privacy-first event hosting platform. |
| **Gatus** | `gatus` | network, development, monitoring | `8080` | Automated developer-oriented status page with highly configurable health checks. Source: https://github.com/TwiN/gatus |
| **Gazee** | `gazee` | media, development | `8080` | A WebApp Comic Reader for your favorite digital comics. Reach and read your comic library from any web connected device with a modern web browser. |
| **Ghost (container)** | `ghost-container` | social | `2368` | Free and open-source blogging platform |
| **Ghost (stack)** | `ghost` | media, social | `8080` | Create your own platform on the web. Ghost is a powerful app for new-media creators to publish, share, and grow a business around their content. It co... |
| **Ghostfolio** | `ghostfolio` | finance, social | `3443` | Ghostfolio is an open source wealth management software built with web technology. |
| **Gimp** | `gimp` | development, productivity | `3000` | [GIMP](https://www.gimp.org/) is a free and open-source raster graphics editor used for image manipulation (retouching) and image editing, free-form d... |
| **Gitea** | `gitea` | development | `3000` | Git with a cup of tea! Painless self-hosted all-in-one software development service, including Git hosting, code review, team collaboration, package r... |
| **GitHub Actions Runner** | `github-runner` | development, data, monitoring | `8080` | A self-hosted GitHub Actions runner: your workflows, your hardware, zero per-minute billing. Uses `myoung34/github-runner` (the de-facto env-driven ru... |
| **Github-desktop** | `github-desktop` | development | `3000` | [Github Desktop](https://desktop.github.com/) is an open source Electron-based GitHub app. It is written in TypeScript and uses React. |
| **Gitlab** | `gitlab` | development | `8080` | Gitlab self-hosted application for Runtipi. |
| **GitLab CE** | `gitlab-ce` | development, productivity | `80` | Open-source end-to-end software development platform |
| **GitLab Runner** | `gitlab-runner` | development | `8080` | A self-hosted GitLab Runner in shell mode: jobs run inside this container, your own compute, no CI-minute quota. Registers itself on first boot and pe... |
| **Gitqlient** | `gitqlient` | development | `3000` | [GitQlient](https://github.com/francescmm/GitQlient) is a multi-platform Git client originally forked from QGit. Nowadays it goes beyond of just a for... |
| **Glance** | `glance` | development, monitoring, social | `8080` | A self-hosted dashboard that puts all your feeds in one place. Source: https://github.com/glanceapp/glance |
| **Glances** | `glances` | network, monitoring | `8080` | Glances is an open-source system cross-platform monitoring tool. It allows real-time monitoring of various aspects of your system such as CPU, memory,... |
| **GlitchTip** | `glitchtip` | development | `5000` | GlitchTip, open-source, Sentry-API-compatible error tracking (point any Sentry SDK at its DSN) at a fraction of self-hosted Sentry's footprint. |
| **Go-Socks5-Proxy** | `socks5-proxy` | security, network, games | `8080` | Simple socks5 server using go-socks5 with authentication options |
| **Goaccessnpm** | `goaccessnpm` | utilities | `7880` | Goaccessnpm self-hosted application for Runtipi. |
| **GoCostWeb** | `gocostweb` | finance | `4000` | Golang-based web application for personal expense management, focused on a clean monthly workflow and intuitive tracking of recurring and non-recurrin... |
| **Gokapi** | `gokapi` | development, data, games | `53842` | Gokapi is a lightweight server to share files, which expire after a set amount of downloads or days. It is similar to the discontinued Firefox Send, w... |
| **Gotenberg** | `gotenberg` | development, productivity, data | `3000` | Docker-powered stateless API for PDF files: conversions, generation, merging, and more. Source: https://github.com/gotenberg/gotenberg |
| **Gotify** | `gotify` | games | `9008` | A simple server for sending and receiving messages |
| **GoToSocial** | `gotosocial` | network, development, productivity | `8080` | An ActivityPub social network server written in Go, providing a lightweight alternative to Mastodon. Source: https://codeberg.org/superseriousbusiness... |
| **Grafana** | `grafana` | development, data, monitoring | `3023` | Grafana is the open source analytics & monitoring solution for every database. |
| **Grafana Dashboard** | `grafana-dashboard` | monitoring | `9993` | Multi-platform open-source interactive visualization web application |
| **Grafana Stack** | `grafana-stack` | development, productivity, data | `5000` | Grafana + Prometheus + Loki - dashboards, metrics, and logs for everything in your project, at a flat price instead of per-host or per-GB-ingested Saa... |
| **Grav** | `grav` | development | `80` | [Grav](https://github.com/getgrav/grav/) is a Fast, Simple, and Flexible, file-based Web-platform. |
| **Grist** | `grist` | development, productivity, data | `8080` | Spreadsheet that works like a database, with typed columns, Python formulas, linked tables, charts and forms. Source: https://github.com/gristlabs/gri... |
| **Grocy (container)** | `grocy` | development | `9283` | [Grocy](https://github.com/grocy/grocy) is an ERP system for your kitchen! Cut down on food waste, and manage your chores with this brilliant utility.... |
| **Guacamole** | `guacamole` | network | `8080` | A clientless remote desktop gateway. |
| **Gzdoom** | `gzdoom` | games | `3000` | [GZDoom](https://gzdoom.app/) is a feature centric port for all Doom engine games, based on ZDoom, adding an OpenGL renderer and powerful scripting ca... |
| **Habridge** | `habridge` | network, development, automation | `8080` | [Habridge](https://github.com/bwssytems/ha-bridge/) emulates Philips Hue API to other home automation gateways such as an Amazon Echo/Dot Gen 1 (gen 2... |
| **Halo** | `halo` | development, social | `8080` | Website and blogging platform with a rich editor, themes, plugins, comments and pages, run from a web console. This one runs on Postgres. Source: http... |
| **Handbrake** | `handbrake` | media, development | `3000` | [HandBrake](https://handbrake.fr/) is an open-source tool, built by volunteers, for converting video from nearly any format to a selection of modern, ... |
| **Hasty-Paste** | `hasty-paste` | productivity | `8080` | Hasty Paste is a fast and minimal paste bin, written in Python using Quart. |
| **Hasura** | `hasura` | development, data | `5000` | Hasura v2 CE - instant GraphQL over Postgres: track tables and get queries, mutations, and live subscriptions with row-level permissions, remote schem... |
| **Hauk** | `hauk` | development, games | `7735` | Hauk is a fully open source, self-hosted location sharing service. Install the backend code on a PHP-compatible web server, install the companion app ... |
| **Headphones** | `headphones` | media, data | `8181` | Headphones is an automated music downloader for NZB and Torrent, written in Python. It supports SABnzbd, NZBget, Transmission, µTorrent and Blackhole. |
| **Healthchecks** | `healthchecks` | development, monitoring, games | `8000` | [Healthchecks](https://github.com/healthchecks/healthchecks) is a watchdog for your cron jobs. It's a web server that listens for pings from your cron... |
| **Hedgedoc** | `hedgedoc` | security, media, development | `3000` | [HedgeDoc](https://hedgedoc.org/) gives you access to all your files wherever you are. HedgeDoc is a real-time, multi-platform collaborative markdown ... |
| **Heimdall** | `heimdall` | development, monitoring | `80` | [Heimdall](https://heimdall.site) is a way to organise all those links to your most used web sites and web applications in a simple way. Simplicity is... |
| **Helium** | `helium` | security | `3000` | [Helium](https://helium.computer/) is a Chromium-based web browser made for people, with love. Privacy-first with unbiased ad-blocking. |
| **Hermes Agent** | `hermes` | development, data, monitoring | `5000` | Hermes Agent (Nous Research), a self-improving AI agent with a learning loop (skills from experience), cron, hooks, and a web dashboard. Official imag... |
| **Hishtory-server** | `hishtory-server` | development, data, games | `8080` | [hiSHtory](https://github.com/ddworken/hishtory) is a better shell history. It stores your shell history in context (what directory you ran the comman... |
| **Hister** | `hister` | development, productivity, games | `8080` | Search engine for your own browsing history. A browser extension sends every page you visit to it, and you search the full text of everything you've r... |
| **Hivekeep** | `hivekeep` | development, productivity, social | `3000` | Self-hosted platform of autonomous, persistent personal AI agents that collaborate, remember, and build their own tools. Reachable via Telegram, Whats... |
| **Hoarder** | `hoarder` | media | `3088` | Hoarder is an open source 'Bookmark Everything' app that uses AI for automatically tagging the content you throw at it. |
| **Homarr (container)** | `homarr` | games | `7575` | Homarr is a simple and lightweight homepage for your server, that helps you easily access all of your services in one place. |
| **Homarr-Secured** | `homarr-secured` | games | `7575` | Homarr is a simple and lightweight homepage for your server, that helps you easily access all of your services in one place. |
| **Homeassistant** | `homeassistant` | security, development, automation | `8123` | [Home Assistant Core](https://www.home-assistant.io/) - Open source home automation that puts local control and privacy first. Powered by a worldwide ... |
| **Homebox** | `homebox` | media, development, productivity | `7745` | Inventory and organization system built for the home user. Source: https://github.com/sysadminsmedia/homebox |
| **Homebridge (container)** | `homebridge` | development, automation | `8080` | Homebridge allows you to integrate with smart home devices that do not natively support HomeKit. There are over 2,000 Homebridge plugins supporting th... |
| **Homebridge - Debian** | `homebridge-debian` | development, automation | `8080` | Debian Homebridge allows you to integrate with smart home devices that do not natively support HomeKit. There are over 2,000 Homebridge plugins suppor... |
| **Homechart** | `homechart` | development, productivity, data | `3030` | Your Budgets, Calendars, Meals, Inventory, Tasks, and so much more in one simple app.For everyone in your household.On all of your devices.In the clou... |
| **Homedex** | `homedex` | security, network, development | `9993` | Read-only inventory for your homelab: services, hosts, ports, routes, certificates, domains and changes, discovered from Docker, Proxmox VE, Tailscale... |
| **HomeLab Monitor** | `homelab-monitor` | development, productivity, monitoring | `8080` | Self-hosted homelab dashboard, one container. Per-container GPU/VRAM attribution (which process holds the card, not just total load), Docker health/lo... |
| **Homepage (container)** | `homepage` | productivity, data, monitoring | `3000` | A modern (fully static, fast), secure (fully proxied), highly customizable application dashboard with integrations for more than 25 services and trans... |
| **Homer** | `homer` | monitoring, games | `8902` | A dead simple static Homepage for your server to keep your services on hand, from a simple yaml configuration file. |
| **Htpcmanager** | `htpcmanager` | media, development | `8085` | [Htpcmanager](https://github.com/HTPC-Manager/HTPC-Manager) is a front end for many htpc related applications. |
| **Httpd** | `httpd` | games | `80` | Open-source HTTP server |
| **Huginn** | `huginn` | utilities | `3000` | Create agents that monitor and act on your behalf. |
| **hydra2** | `hydra2` | development, data | `5076` | NZBHydra is a meta search for NZB indexers and the "spiritual successor" to NZBmegasearcH. It provides easy access to a number of raw and newznab base... |
| **I hate money** | `ihatemoney` | finance | `8080` | I hate money is a web application made to ease shared budget management. It keeps track of who bought what, when, and for whom; and helps to settle th... |
| **Immich** | `immich` | media, development, data | `8080` | Immich is a high performance self-hosted photo and video backup solution. |
| **Inductive Automation - Ignition Gateway** | `inductive-automation-ignition-gateway` | network, data, automation | `9993` | Ignition Gateway is the primary software service that drives everything in Ignition - Single Server Deployment |
| **Infisical** | `infisical` | security, development, productivity | `5000` | Infisical - the open-source secrets manager: projects with environments, secret versioning, references, dynamic secrets, and first-class integrations ... |
| **Influxdb** | `influxdb2` | development, data, monitoring | `8086` | InfluxDB is an open source time series database for recording metrics, events, and analytics. |
| **Influxdb & Telegraf** | `influxdb-telegraf` | development, data, monitoring | `8086` | InfluxDB is an open source time series database for recording metrics, events, and analytics. Telegraf is an agent for collecting metrics and writing ... |
| **Influxdb 1.8.10** | `influxdb1810` | development, data, monitoring | `8086` | InfluxDB is an open source time series database for recording metrics, events, and analytics. |
| **InfluxDB for Edge** | `influxdb-for-edge` | data, games | `9993` | InfluxDB Time Series Data Platformm - Single Server deployment |
| **Influxdb2_Telegraf** | `influxdb2-telegraf` | utilities | `8086` | Influxdb2_Telegraf self-hosted application for Runtipi. |
| **Inkscape** | `inkscape` | utilities | `3000` | [Inkscape](https://inkscape.org/) is professional quality vector graphics software which runs on Linux, Mac OS X and Windows desktop computers. |
| **Intellij-idea** | `intellij-idea` | development, productivity | `3000` | [IntelliJ IDEA](https://www.jetbrains.com/idea/) helps you write code faster with tools that eliminate tedious tasks and let you focus on what matters... |
| **Invidious** | `invidious` | media | `3333` | Invidious is an open source alternative front-end to YouTube. |
| **Invoice Ninja (stack)** | `invoice-ninja` | productivity, data, finance | `8080` | Invoices, Expenses and Tasks built with Laravel and Flutter. |
| **iobroker** | `iobroker` | development, automation, monitoring | `8081` | IoBroker is a open source IoT platform written in JavaScript that easily connects smarthome components from different manufactures. With the help of p... |
| **iperf** | `iperf` | network, productivity | `5201` | IPerf3 Docker Build for Network Performance and Bandwidth Testing |
| **IronFunctions** | `ironfunctions` | games | `8080` | Open-source serverless computing platform |
| **IronFunctions API** | `ironfunctions-api` | development, games | `8080` | Open-source serverless computing platform |
| **IronFunctions UI** | `ironfunctions-ui` | games | `4000` | Open-source user interface for IronFunctions |
| **IT-Tools** | `it-tools` | development, productivity | `8080` | Collection of handy online tools for developers, with great UX. Source: https://github.com/CorentinTh/it-tools |
| **Jackett** | `jackett` | media, network, development | `9117` | [Jackett](https://github.com/Jackett/Jackett) works as a proxy server: it translates queries from apps (Sonarr, SickRage, CouchPotato, Mylar, etc) int... |
| **JDownloader** | `jdownloader` | productivity, data | `3129` | JDownloader docker image |
| **Jellyfin (container)** | `jellyfin` | media, development, games | `8096` | [Jellyfin](https://github.com/jellyfin/jellyfin) is a Free Software Media System that puts you in control of managing and streaming your media. It is ... |
| **Jellyfin-Accounts** | `jfa-go` | media, development | `8056` | jfa-go is a user management app for Jellyfin (and now Emby) that provides invite-based account creation as well as other features that make one's inst... |
| **Jellyseer** | `jellyseer` | media | `5055` | Jellyseerr is a free and open source fork of Overseerr for managing requests for your media library. It integrates with your existing services, such a... |
| **Jellyseerr** | `jellyseerr` | media | `5055` | Jellyseer is a free and open source software application for managing requests for your media library. |
| **Jenkins (container)** | `jenkins-container` | utilities | `8080` | Open-source continuous integration tool |
| **Jenkins (stack)** | `jenkins` | development, automation, games | `5000` | Jenkins LTS - the automation server: pipelines as code, 1,800+ plugins, and webhooks from every forge. Controller with the built-in node, which runs j... |
| **Joomla** | `joomla` | utilities | `80` | Another free and open-source CMS |
| **Joplin** | `joplin` | media, productivity | `3000` | [Joplin](https://joplinapp.org/) is a free, open source note taking and to-do application, which can handle a large number of notes organised into not... |
| **Jump** | `jump` | monitoring, games | `9123` | Jump is yet another self-hosted startpage for your server designed to be simple, stylish, fast and secure. |
| **JupyterLab** | `jupyterlab` | media, development, productivity | `8888` | Python notebooks in the browser for poking at data and plotting it, with a terminal alongside. It's Jupyter's scipy-notebook image, so pandas, NumPy, ... |
| **Kali-linux** | `kali-linux` | security, network, development | `3000` | [Kali-linux](https://github.com/linuxserver/docker-kali-linux) - is an Advanced Penetration Testing Linux distribution used for Penetration Testing, E... |
| **Kanboard** | `kanboard` | development, productivity | `8094` | Kanban project management that stays out of the way, with boards, swimlanes, subtasks, time tracking, automatic actions and a plugin system. Source: h... |
| **Kaneo** | `kaneo` | development, productivity, data | `8080` | Project management for small teams: kanban boards, a backlog, Gantt charts, labels, time tracking and GitHub, GitLab or Gitea issue sync, in workspace... |
| **Kapowarr** | `kapowarr` | media | `5656` | Kapowarr is a software to build and manage a comic book library, fitting in the *arr suite of software. |
| **Karakeep** | `karakeep` | media, productivity | `5000` | Karakeep (formerly Hoarder) - a self-hosted "bookmark everything" app: save links, notes, and images, and it automatically crawls and archives the pag... |
| **Kasm** | `kasm` | media, development, productivity | `3000` | [Kasm](https://www.kasmweb.com/?utm_campaign=LinuxServer&utm_source=listing) Workspaces is a docker container streaming platform for delivering browse... |
| **Kasm Workspaces** | `kasmworkspaces` | media, development, productivity | `63000` | The Workspace Streaming Platform.Stream your workspace directly to your web browser on any device and from any location. |
| **Kavita** | `kavita` | media, development, games | `5000` | [Kavita](https://github.com/Kareadita/Kavita) is a fast, feature rich, cross platform reading server. Built with a focus for being a full solution for... |
| **Kdenlive** | `kdenlive` | media, development | `3000` | [Kdenlive](https://kdenlive.org/) is a powerful free and open source cross-platform video editing program made by the KDE community. Feature rich and ... |
| **Keepassxc** | `keepassxc` | security | `3000` | [KeePassXC](https://keepassxc.org/) is a free and open-source password manager. It started as a community fork of KeePassX (itself a cross-platform po... |
| **Kener** | `kener` | security, network, development | `8080` | Status page with built-in monitoring: it checks your sites, APIs, ports and DNS on a schedule and shows uptime, response times, incidents and planned ... |
| **Kestra** | `kestra` | development, automation | `8080` | Powerful orchestration. Simplified workflows.Unify orchestration for all engineers. Build and govern all your workflows — Everything-as-Code, and from... |
| **Keycloak** | `keycloak` | security, network, development | `5000` | Keycloak, identity & access management (OIDC, SAML, social login, user federation) backed by a managed Postgres. |
| **Kicad** | `kicad` | automation | `3000` | [KiCad](https://www.kicad.org/) - A Cross Platform and Open Source Electronics Design Automation Suite. |
| **Kilo (headless)** | `kilo` | development, data, games | `5000` | Kilo, open-source AI coding agent, running in server mode (`kilo serve`) on Miget: a persistent remote agent whose HTTP+SSE API your Kilo clients atta... |
| **Kimai** | `kimai` | security, development, productivity | `80` | [Kimai](https://kimai.org/) is a professional grade time-tracking application, free and open-source. It handles use-cases of freelancers as well as co... |
| **KitchenOwl** | `kitchenowl` | development, productivity, data | `8080` | Grocery list and recipe manager for households, with shopping lists that sync live between everyone, recipes you can add to the list in one go, a meal... |
| **Klaxon** | `klaxon` | productivity | `9993` | Klaxon is a free, quick to set up and easy to use robot that checks websites regularly so you don't have to. |
| **Kodi Headless** | `kodi-headless` | media, development | `8080` | Headless installation of Kodi™ (formerly known as XBMC™), to enable library updates. |
| **Koillection** | `koillection` | media, games | `181` | Koillection is a self-hosted collection manager created to keep track of physical (mostly) collections of any kind like books, DVDs, stamps, games.. |
| **Kometa** | `kometa` | media, development, data | `80` | [Kometa](https://github.com/Kometa-Team/Kometa) is a powerful tool designed to give you complete control over your media libraries. With Kometa, you c... |
| **Komga** | `komga` | media, games | `8995` | Komga is a free and open source comics/mangas/magazines server. |
| **Kong Gateway** | `kong` | security, network, development | `5000` | DB-backed Kong Gateway (OSS) in front of your project's apps, deployable locally with plain Docker Compose or to Miget as a compose stack. |
| **Krita** | `krita` | development | `3000` | [Krita](https://krita.org/en/) is a professional FREE and open source painting program. It is made by artists that want to see affordable art tools fo... |
| **Langflow** | `langflow` | development, automation, social | `8080` | Visual builder for AI agents and workflows: drag together models, prompts, tools, vector stores and MCP servers on a canvas, chat with the result in a... |
| **Langfuse** | `langfuse` | development, monitoring | `5000` | Langfuse v3 - open-source LLM engineering platform: tracing, evaluations, prompt management, and usage dashboards. This template mirrors the official ... |
| **Lazylibrarian** | `lazylibrarian` | security, media, development | `5299` | [Lazylibrarian](https://lazylibrarian.gitlab.io/) is a program to follow authors and grab metadata for all your digital reading needs. It uses a combi... |
| **Lazytainer** | `lazytainer` | network, productivity | `81` | Lazytainer monitors network traffic to containers. If there is traffic, the container runs, otherwise the container is stopped/paused. |
| **Ldap-auth** | `ldap-auth` | security, network, development | `8888` | [Ldap-auth](https://github.com/nginxinc/nginx-ldap-auth) software is for authenticating users who request protected resources from servers proxied by ... |
| **Leantime** | `leantime` | development, productivity | `8080` | Leantime is an open source project management solution to make your ideas reality. |
| **Let's Encrypt** | `letsencrypt` | security, network, development | `80` | This container sets up an Nginx webserver and reverse proxy with php support and a built-in letsencrypt client that automates free SSL server certific... |
| **Let's Encrypt / SWAG** | `letsencrypt-swag` | security, network, games | `80` | This container sets up an Nginx webserver and reverse proxy with php support and a built-in letsencrypt client that automates free SSL server certific... |
| **Letta** | `letta` | development, games | `5000` | Letta (the MemGPT lineage) - an agent server with memory as the core primitive: agents live server-side with self-editing persistent memory, and clien... |
| **LibreDB Studio** | `libredb-studio` | development, data, games | `3006` | Self-hosted database IDE you use from a browser, covering forty-two engines - PostgreSQL, MySQL, Oracle, SQL Server, MongoDB, Redis, ClickHouse, Cassa... |
| **libreddit** | `libreddit` | utilities | `8088` | An alternative private front-end to Reddit |
| **Libreoffice** | `libreoffice` | productivity | `3000` | [LibreOffice](https://www.libreoffice.org/) is a free and powerful office suite, and a successor to OpenOffice.org (commonly known as OpenOffice). Its... |
| **libresonic** | `libresonic` | media, network, data | `4040` | Libresonic is a free, web-based media streamer, providing ubiqutious access to your music. Use it to share your music with friends, or to listen to yo... |
| **Librespeed** | `librespeed` | network, development, monitoring | `80` | [Librespeed](https://github.com/librespeed/speedtest) is a very lightweight Speedtest implemented in Javascript, using XMLHttpRequest and Web Workers.... |
| **LibreTranslate** | `libretranslate` | development, productivity, games | `8080` | Machine translation server with a page for translating text and documents, plus a JSON API for other apps to call. Runs its own models, so nothing you... |
| **Librewolf** | `librewolf` | security, data | `3000` | [LibreWolf](https://librewolf.net/) is a custom and independent version of Firefox, with the primary goals of privacy, security and user freedom. Libr... |
| **Lidarr** | `lidarr` | media, development, data | `8686` | [Lidarr](https://github.com/lidarr/Lidarr) is a music collection manager for Usenet and BitTorrent users. It can monitor multiple RSS feeds for new tr... |
| **Lidify** | `lidify` | media | `8080` | Self-hosted, on-demand audio streaming platform that brings the Spotify experience to your personal music library. Features music streaming, podcast s... |
| **Lidify Full** | `lidify-full` | utilities | `8080` | Lidify Full self-hosted application for Runtipi. |
| **Limnoria** | `limnoria` | development | `8080` | [Limnoria](https://github.com/ProgVal/limnoria) A robust, full-featured, and user/programmer-friendly Python IRC bot, with many existing plugins. Succ... |
| **LinkAce** | `linkace` | media, development, productivity | `8080` | Bookmark archive for keeping links you want to come back to, with tags, lists, notes, private or shared links, a browser bookmarklet, imports from any... |
| **Linkding** | `linkding` | media, development, productivity | `9090` | Self-hosted bookmark manager that is minimal and fast. Source: https://github.com/sissbruecker/linkding |
| **Linkstack** | `linkstack` | development, social | `8188` | Self-hosted open-source Linktree alternative. LinkStack is a highly customizable link sharing platform with an intuitive, easy to use user interface. |
| **Linkwarden** | `linkwarden` | media, productivity, finance | `5000` | Linkwarden - a bookmark manager that actually keeps your links: every save is preserved as a screenshot, PDF, readable HTML, and an archive.org snapsh... |
| **Listmonk** | `listmonk` | development, productivity, monitoring | `9000` | High performance self-hosted newsletter and mailing list manager with a modern dashboard. Source: https://github.com/knadh/listmonk |
| **LiteLLM** | `litellm` | network, development, finance | `5000` | LiteLLM proxy - one OpenAI-compatible endpoint in front of every LLM provider (Anthropic, OpenAI, Gemini, Bedrock, Mistral, local, …) with virtual key... |
| **Litmus Edge** | `litmus-edge` | data | `9993` | Litmus Edge is an edge data platform that enables industrial AI at scale. It connects, processes, and analyzes real-time OT data at the edge to power ... |
| **Litmus Edge Digital Factory Demo** | `litmus-edge-digital-factory-demo` | development, data | `9993` | Demo System for Litmus Edge. Litmus Edge is an edge data platform that enables industrial AI at scale. It connects, processes, and analyzes real-time ... |
| **Littlelink** | `littlelink` | utilities | `8480` | Littlelink self-hosted application for Runtipi. |
| **Littlelink Server** | `littlelink-server` | development, social, games | `8480` | LittleLink is an open source DIY self-hosted alternative to services like Linktree and many.link. |
| **Livebook** | `livebook` | media, development | `8080` | Interactive Elixir notebooks saved as plain Markdown, with charts, tables, maps and forms built in, plus a way to turn a notebook into a small web app... |
| **LiveKit** | `livekit` | media, development, games | `5000` | LiveKit - the Apache-2.0 WebRTC server powering modern voice agents and video apps: rooms, tracks, selective forwarding, and the Agents framework ecos... |
| **LiveKit Agents** | `livekit-agents` | network | `8080` | A voice AI agent worker on the LiveKit Agents framework: it joins LiveKit rooms and converses - Deepgram for ears, ElevenLabs for voice, any OpenAI-co... |
| **LiveSwitch (stack)** | `liveswitch-stack` | media, network, development | `9993` | A basic LiveSwitch compose with gateway, caching, database and media server |
| **LiveSwitch (swarm)** | `liveswitch-swarm` | media, network, development | `8080` | A basic LiveSwitch stack with gateway, caching, database and media server |
| **LLDAP** | `lldap` | security, development, productivity | `3890` | This project is a lightweight authentication server that provides an opinionated, simplified LDAP interface for authentication. |
| **Lm-studio** | `lm-studio` | utilities | `3000` | [LM Studio](https://lmstudio.ai/) can run local AI models like gpt-oss, Llama, Gemma, Qwen, and DeepSeek privately on your computer. |
| **Loggifly** | `loggifly` | productivity, monitoring | `8080` | A Lightweight Tool that monitors Docker Container Logs for predefined keywords or regex patterns and sends Notifications. |
| **Logto** | `logto` | security, network, development | `5000` | Logto - the open-source Auth0 experience: pre-built hosted sign-in pages, OIDC/OAuth, social logins, organizations, MFA, and clean SDKs for every fram... |
| **Logzio Logs Collector** | `logzio-logs-collector` | productivity, monitoring | `8080` | Docker container that uses Filebeat to collect logs from other Docker containers and forward those logs to your Logz.io account. |
| **Logzio Metrics Collector** | `logzio-metrics-collector` | productivity, monitoring | `8080` | Docker Metrics Collector is a container that runs Metricbeat with the modules you enable at runtime. |
| **Lollypop** | `lollypop` | media, productivity | `3000` | [Lollypop](https://wiki.gnome.org/Apps/Lollypop) is a lightweight modern music player designed to work excellently on the GNOME desktop environment. |
| **Luanti** | `luanti` | games | `30000` | [Luanti](https://www.luanti.org/) (formerly Minetest) is an open source voxel game-creation platform with easy modding and game creation |
| **LubeLogger** | `lubelogger` | development, productivity, finance | `8180` | Vehicle maintenance and fuel tracker: log services, repairs, fuel-ups, taxes and odometer readings for each car, attach receipts, and get reminders wh... |
| **Lunalytics** | `lunalytics` | data, monitoring | `2308` | Open source monitoring tool built with Node.js & React |
| **Lychee** | `lychee` | media, development, games | `80` | [Lychee](https://lycheeorg.github.io/) is a free photo-management tool, which runs on your server or web-space. Installing is a matter of seconds. Upl... |
| **LynxPrompt** | `lynxprompt` | development, productivity | `3000` | Self-hostable AI config management platform for AGENTS.md, CLAUDE.md, Cursor rules, and 30+ AI assistant formats. Source: https://github.com/GeiserX/L... |
| **MaestroHub** | `maestrohub` | data, games | `9993` | Industrial data orchestrator with a Unified Namespace, drag-and-drop pipelines, and 40+ protocol connectors. Built-in MCP server brings AI agents into... |
| **Magento 2** | `magento-2` | utilities | `80` | Open-source e-commerce platform |
| **Mailpile** | `mailpile` | productivity, games | `33411` | Mailpile is an e-mail client!/search engine and a personal webmail server/easy way to encrypt your e-mail/easy way to encrypt your e-mail |
| **Mailpit** | `mailpit` | development, productivity | `5000` | Mailpit - the modern dev mail catcher (MailHog's actively-maintained successor, MIT): an SMTP sink plus a fast web UI with search, HTML preview, link ... |
| **Maintainerr** | `maintainerr` | media, development | `6246` | Library tidier for Plex, Jellyfin and Emby. You write rules like "nobody's watched it in six months", it gathers what matches into a leaving-soon coll... |
| **Maloja** | `maloja` | media, network, development | `42010` | Simple self-hosted music scrobble database to create personal listening statistics. No recommendations, no social network, no nonsense. |
| **Mame** | `mame` | media, development, monitoring | `3000` | [MAME](https://www.mamedev.org/) is a free and open-source emulator designed to emulate the hardware of arcade games, video game consoles, old compute... |
| **ManaWG** | `manawg` | development, productivity, data | `5000` | Free, open-source app for shared flats: expenses, cleaning rota, shopping list, calendar and chat. Runs the app with PostgreSQL, sign-in and image sto... |
| **Manubes Edge Node** | `manubes-edge-node` | development, data | `9993` | High-performance cloud platform for industrial production management. Manubes is a no-code solution that is used to structure, monitor and control pro... |
| **Manyfold** | `manyfold` | development | `3214` | [Manyfold](https://github.com/manyfold3d/manyfold/) is an open source, self-hosted web application for managing a collection of 3D models, particularl... |
| **MariaDB (container)** | `mariadb-container` | development, data | `3306` | Performance beyond MySQL |
| **MariaDB (stack)** | `mariadb` | development, data | `3306` | MariaDB 11.8 - the community-developed MySQL fork, as a single self-hosted node. Drop-in compatible with MySQL for most applications, configured throu... |
| **MariaDB Galera** | `mariadb-galera` | development, data | `8080` | 3-node MariaDB 11.8 LTS cluster with Galera synchronous multi-primary replication - every node accepts writes, any node can die. Runs the OFFICIAL mar... |
| **MariaDB Replication** | `mariadb-replication` | development, data | `3307` | Asynchronous MariaDB replication: one primary accepts writes and streams its binary log to a read-only replica. This is the classic read-scaling / hot... |
| **marimo** | `marimo` | media, development, data | `8080` | Python notebooks saved as plain .py files, where running a cell reruns everything that depends on it, with SQL cells, interactive widgets and a datafr... |
| **Markopolis** | `markopolis` | productivity | `8080` | Markopolis is like the self hosted version of Obsidian Publish. |
| **Marreta** | `marreta` | utilities | `1180` | Marreta is a tool that breaks down access barriers and elements that hinder reading! |
| **Mastodon (container)** | `mastodon` | network, development, productivity | `80` | [Mastodon](https://github.com/mastodon/mastodon/) is a free, open-source social network server based on ActivityPub where users can follow friends and... |
| **Mathesar** | `mathesar` | development, productivity, data | `8080` | Spreadsheet-like interface for PostgreSQL, for browsing, editing and linking tables without SQL, building queries by pointing and clicking and importi... |
| **Matomo** | `matomo` | security, data | `8282` | Google Analytics alternative that protects your data and your customers' privacy |
| **Mattermost** | `mattermost` | network, development, social | `5000` | Mattermost - open-source team chat: channels, threads, DMs, voice calls, slash commands, integrations, and plugins. Team Edition image on a managed Po... |
| **Mautic (container)** | `mautic-container` | automation | `80` | Open-source marketing automation platform |
| **Mautic (stack)** | `mautic` | development, automation | `9855` | Mautic provides free and open source marketing automation software available to everyone. |
| **Mayan EDMS** | `mayan` | security, productivity | `9993` | Mayan EDMS is an electronic vault for your documents. |
| **McMyAdmin 2** | `mcmyadmin2` | games | `8080` | McMyAdmin 2 is the leading web control panel and administration console for Minecraft servers. |
| **Mealie** | `mealie` | development | `9925` | A self-hosted recipe manager and meal planner |
| **Medama** | `medama` | productivity, data | `8010` | Medama Analytics is an open-source project dedicated to providing self-hostable, cookie-free website analytics. |
| **Media_Server_Plex** | `media-server-plex` | media, games | `8080` | Media_Server_Plex self-hosted application for Runtipi. |
| **Mediaelch** | `mediaelch` | security, media, development | `3000` | [MediaElch](https://github.com/Komet/MediaElch) is a MediaManager for Kodi. Information about Movies, TV Shows, Concerts and Music are stored as nfo f... |
| **Medusa (container)** | `medusa` | media, development | `8081` | [Medusa](https://pymedusa.com/) is an automatic Video Library Manager for TV Shows. It watches for new episodes of your favorite shows, and when they ... |
| **Meilisearch** | `meilisearch` | development | `7700` | Meilisearch is a **RESTful search API**. It aims to be a **ready-to-go solution** for everyone who wants a **fast and relevant search experience** for... |
| **Melonds** | `melonds` | games | `3000` | [melonDS](https://melonds.kuribo64.net/) aims at providing fast and accurate Nintendo DS emulation. |
| **Memos** | `memos` | development, productivity | `5000` | Memos - the lightweight note hub: quick markdown notes with tags, search, and selective sharing. A single Go binary on SQLite, MIT-licensed - the "cap... |
| **Mermaid Live Editor** | `mermaid-live-editor` | development | `8980` | Browser editor for Mermaid diagrams, previewing flowcharts, sequence, class, Gantt and dozens of other diagram types live as you write them in plain t... |
| **Meshcentral** | `meshcentral` | network, games | `8080` | MeshCentral is a full computer management web site. With MeshCentral, you can run your own web server to remotely manage and control computers on a lo... |
| **Metabase** | `metabase` | development, data, finance | `5000` | Metabase OSS - the BI tool non-analysts actually use: point-and-click questions, dashboards, and SQL when you want it. One JVM container + a managed P... |
| **MeTube** | `metube` | media, development, data | `8081` | Web GUI for youtube-dl (using the yt-dlp fork) with playlist support. Allows you to download videos from YouTube and dozens of other sites (https://gi... |
| **Microsoft OMS Agent** | `microsoft-oms-agent` | utilities | `8080` | Microsoft Operations Management Suite Linux agent. |
| **Midarr** | `midarr` | media, games | `4000` | Your media enjoyed through a minimal lightweight media server. |
| **Minecraft Server (container)** | `minecraft` | development, productivity, data | `25565` | This docker image provides a Minecraft Server that will automatically download the latest stable version at startup. You can also run/upgrade to any s... |
| **Minetest** | `minetest` | games | `30000` | Server version of minetest, a free, open source alternative to minecraft. |
| **Miniflux** | `miniflux` | social | `8080` | Miniflux is a minimalist and opinionated feed reader. |
| **Minio (container)** | `minio-container` | development, data, games | `9000` | A distributed object storage server built for cloud applications and devops |
| **MinIO (stack)** | `minio` | data | `5000` | MinIO, S3-compatible object storage, single node + 20 GB volume, with the web console as the public entrypoint. |
| **Minisatip** | `minisatip` | media, development, games | `8875` | [Minisatip](https://github.com/catalinii/minisatip) is a multi-threaded satip server version 1.2 that runs under Linux and it was tested with DVB-S, D... |
| **Modmanager** | `modmanager` | development, productivity, games | `80` | # This container needs special attention. Please check https://hub.docker.com/r/linuxserver/modmanager for details. |
| **Modrinth** | `modrinth` | games | `3000` | [Modrinth App](https://modrinth.com/) is a unique, open source launcher that allows you to play your favorite mods, and keep them up to date, all in o... |
| **Mongo** | `mongo` | development, productivity, data | `27017` | Open-source document-oriented database |
| **MongoDB Replica Set** | `mongodb` | development, productivity, data | `27017` | 3-node MongoDB 8 replica set (`rs0`), deployable locally with plain Docker Compose or to Miget as a compose stack. |
| **Monica** | `monica` | development, social | `818` | Monica is a great open source personal relationship management system to organize the interactions with your loved ones. |
| **Moodle** | `moodle` | development | `8080` | Moodle is a learning platform designed to provide educators, administrators and learners with a single robust, secure and integrated system to create ... |
| **Mozilla Syncserver** | `syncserver` | data, games | `5000` | Run-Your-Own Firefox Sync Server |
| **Msedge** | `msedge` | development | `3000` | [Microsoft Edge](https://www.microsoft.com/edge) is a cross-platform web browser developed by Microsoft and based on Chromium. |
| **Mstream** | `mstream` | media, development, games | `3000` | [Mstream](https://mstream.io/) is a personal music streaming server. You can use mStream to stream your music from your home computer to any device, a... |
| **Mullvad-browser** | `mullvad-browser` | security, network, development | `3000` | The [Mullvad Browser](https://mullvad.net/en/browser) is a privacy-focused web browser developed in a collaboration between Mullvad VPN and the Tor Pr... |
| **Murmur** | `murmur` | social, games | `64738` | Mumble is a voicechat program for gamers written on top of Qt and Opus. Murmur is the server backend for Mumble. |
| **MusicBrainz** | `musicbrainz` | media, data | `5000` | MusicBrainz is an open music encyclopedia that collects music metadata and makes it available to the public. |
| **Muximux** | `muximux` | media, games | `80` | A lightweight portal to view, manage your HTPC apps without having to run anything more than a PHP enabled webserver. With Muximux you don't need to k... |
| **MyIP** | `myip` | security, network, development | `8080` | IP toolbox for checking your own connection: your IPv4 and IPv6 addresses and where they look like they are, which sites you can reach, WebRTC and DNS... |
| **Mylar** | `mylar` | media, data | `8090` | An automated Comic Book downloader (cbr/cbz) for use with SABnzbd, NZBGet and torrents. |
| **Mylar3** | `mylar3` | media, development, data | `8090` | [Mylar3](https://github.com/MylarComics/mylar3) is an automated Comic Book downloader (cbr/cbz) for use with NZB and torrents written in python. It su... |
| **MySQL (container)** | `mysql-container` | development, data | `3306` | The most popular open-source database |
| **MySQL (stack)** | `mysql` | development, data | `3306` | MySQL 8.4 LTS - the world's most popular open- source relational database, as a single self-hosted node. Configured entirely through the official imag... |
| **MySQL InnoDB Cluster** | `mysql-innodb-cluster` | development, data | `3306` | 3-node high availability using MySQL Group Replication - the engine that MySQL InnoDB Cluster is built on. |
| **Mysql-workbench** | `mysql-workbench` | development, data, games | `3000` | [MySQL Workbench](https://www.mysql.com/products/workbench/) is a unified visual tool for database architects, developers, and DBAs. MySQL Workbench p... |
| **n8n (container)** | `n8n` | data, automation | `5678` | n8n allows you to build flexible workflows focused on deep data integration. |
| **NATS Cluster** | `nats` | media, social | `8080` | NATS - the lightweight, blazing-fast messaging system: subjects, pub/sub, request/reply, and JetStream for persistent streams and key-value/object sto... |
| **Navidrome** | `navidrome` | media, development, games | `4533` | Navidrome is an open source web-based music collection server and streamer. It gives you freedom to listen to your music collection from any browser o... |
| **Neko** | `neko` | utilities | `8080` | Simple room management system for n.eko. Self hosted rabb.it alternative. --Please add .env file as stated in neko.yml |
| **NetAlertX** | `netalertx` | network, development, monitoring | `8080` | WIFI / LAN intruder detector. Scans for devices connected to your network and alerts you if new and unknown devices are found. |
| **Netboot.xyz (container)** | `netbootxyz` | media, data | `3000` | Netbootxyz is a way to PXE boot various operating system installers or utilities from one place within the BIOS without the need of having to go retri... |
| **Netboot.xyz (stack)** | `netboot-xyz` | development | `3300` | netboot.xyz is a convenient place to boot into any type of operating system or utility disk without the need of having to go spend time retrieving the... |
| **Netbox** | `netbox` | network, development, data | `8000` | [Netbox](https://github.com/netbox-community/netbox) is an IP address management (IPAM) and data center infrastructure management (DCIM) tool. Initial... |
| **Netdata** | `netdata` | data, monitoring | `19999` | Troubleshoot slowdowns and anomalies in your infrastructure with thousands of per-second metrics, meaningful visualizations, and insightful health ala... |
| **Nextcloud (container)** | `nextcloud` | media, development, productivity | `443` | [Nextcloud](https://nextcloud.com/) gives you access to all your files wherever you are. Where are your photos and documents? With Nextcloud you pick ... |
| **NextcloudStack (swarm)** | `nextcloudstack-swarm` | development, data | `8080` | Nextcloud setup with a MySQL database |
| **Nexterm** | `nexterm` | games | `6989` | The open source server management software for SSH, VNC & RDP |
| **Nginx** | `nginx` | network, games | `80` | High performance web server |
| **Nginx Proxy Manager (container)** | `nginx-proxy-manager` | network | `80` | Nginx Proxy Manager enables you to easily forward to your websites running at home or otherwise, including free SSL, without having to know too much a... |
| **Nginx Proxy Manager (stack)** | `npm` | network | `8000` | Nginx Proxy Manager enables you to easily forward to your websites running at home or otherwise, including free SSL, without having to know too much a... |
| **Nginx Proxy Manager v2 with Sqllite** | `nginx-proxy-manager-sqlite` | network, development, productivity | `80` | Nginx Proxy Manager v2 with Sqlite enables you to easily forward to your websites running at home or otherwise, including free SSL, without having to ... |
| **Nginx Proxy Manager v3 [DEVEL] NOT READY FOR USE** | `nginx-proxy-manager-v3` | network, development, productivity | `80` | [DEVEL] Not ready for production. Nginx Proxy Manager v3 Develop enables you to easily forward to your websites running at home or otherwise, includin... |
| **Ngircd** | `ngircd` | security, network, development | `6667` | [Ngircd](https://ngircd.barton.de/) is a free, portable and lightweight Internet Relay Chat server for small or private networks, developed under the ... |
| **NocoBase** | `nocobase` | development, productivity, data | `8080` | No-code platform for building internal tools and business apps: define your own data tables and relations, then build pages, forms, kanbans and calend... |
| **NocoDB** | `nocodb` | development, productivity, games | `8585` | Turns any MySQL, PostgreSQL, SQL Server, SQLite & MariaDB into a smart-spreadsheet. |
| **Node-Red** | `node-red` | development, data | `9993` | Low-code programming for event-driven applications |
| **NodeBB** | `nodebb` | development, social | `8080` | Forum software with a modern feel: categories, topics and replies that update live, chat, notifications, groups, Markdown with image uploads, and a pl... |
| **NodeJS** | `nodejs` | network, development, games | `8080` | JavaScript-based platform for server-side and networking applications |
| **Nodered** | `nodered` | automation | `1880` | Nodered self-hosted application for Runtipi. |
| **Nomacs** | `nomacs` | development | `3000` | [Nomacs](https://github.com/nomacs/nomacs) is a free, open source image viewer, which supports multiple platforms. You can use it for viewing all comm... |
| **nord-vpn** | `nord-vpn` | security, network, productivity | `8080` | This is an OpenVPN client docker container that uses recommended NordVPN server. It makes routing containers traffic through OpenVPN easy. |
| **ntfy (container)** | `ntfy` | development, social | `8080` | Simple HTTP-based pub-sub notification service. Send push notifications to your phone or desktop via PUT/POST. Source: https://github.com/binwiederhie... |
| **NUT Server** | `nut-server` | development, games | `3493` | The purpose of NUT Server is to monitor a UPS attached device |
| **Nutify** | `nutify` | development, monitoring | `3493` | Nutify is a comprehensive monitoring system designed to track the health and performance of your Uninterruptible Power Supply (UPS) devices. |
| **NUTS** | `nuts` | network, games | `3493` | Network UPS Tools server |
| **Nzbget** | `nzbget` | data | `6789` | [Nzbget](http://nzbget.com/) is a usenet downloader, written in C++ and designed with performance in mind to achieve maximum download speed by using v... |
| **Nzbhydra2** | `nzbhydra2` | development | `5076` | [Nzbhydra2](https://github.com/theotherp/nzbhydra2) is a meta search application for NZB indexers, the spiritual successor to NZBmegasearcH, and an ev... |
| **Obsidian** | `obsidian` | development, productivity, data | `3000` | [Obsidian](https://obsidian.md) is a note-taking app that lets you create, link, and organize your notes on your device, with hundreds of plugins and ... |
| **OctoPrint** | `octoprint` | development | `8051` | OctoPrint is an open source 3D printer controller application, which provides a web interface for the connected printers. |
| **Odoo (container)** | `odoo-container` | productivity | `8069` | Open-source business apps |
| **Odoo (stack)** | `odoo` | development, productivity, finance | `5000` | Odoo Community 18 - the open-source business suite: CRM, sales, inventory, accounting, projects, manufacturing, website, and ecommerce, with a vast ap... |
| **Ollama** | `ollama` | development | `5000` | Ollama - run open large language models locally behind a simple HTTP API. Pull a model (Llama, Mistral, Qwen, Gemma, Phi, and many more) and serve it ... |
| **Omada EAP Controller** | `omada-controller` | network | `8088` | TP-Link Omada is a software-defined network solution. The EAP Controller is used to manage multiple EAPs. Raspberry Pi 1 and Zero are not supported. |
| **Ombi (container)** | `ombi` | media, productivity, games | `3579` | [Ombi](https://ombi.io) allows you to host your own Plex Request and user management system. If you are sharing your Plex server with other users, all... |
| **OmniTools** | `omnitools` | media, development, productivity | `8920` | Toolbox of over a hundred small utilities for images, PDFs, video, audio, text, JSON, CSV and lists, like resizing, compressing, merging, trimming and... |
| **Onlyoffice** | `onlyoffice` | development, productivity, data | `3000` | [ONLYOFFICE](https://www.onlyoffice.com/) provides a full range of tools to create, edit and collaborate on text documents, spreadsheets, presentation... |
| **OPC Router** | `opc-router` | development, productivity, data | `9993` | No-code middleware for industrial applications The OPC Router connects PLCs, PCS, SCADA, MES, SQL databases and servers, label printers, e-mail server... |
| **Open Mercato** | `open-mercato` | productivity | `5000` | Open Mercato - the MIT "AI-engineering foundation framework": multi-tenant CRM/ERP/commerce modules on Next.js with RBAC, dynamic entities, and an age... |
| **Open WebUI** | `open-webui` | development, productivity, social | `5000` | Open WebUI - the self-hosted AI chat workspace: ChatGPT-style UI over any OpenAI-compatible API, with RAG over uploaded documents, multi-user accounts... |
| **OpenAMT** | `openamt` | data | `9993` | OpenAMT Cloud Toolkit |
| **OpenBudgeteer** | `openbudgeteer` | development, finance | `8081` | OpenBudgeteer is a budgeting app based on the Bucket Budgeting Principle and inspired by YNAB and Buckets. |
| **OpenClaw** | `openclaw` | network, productivity, data | `5000` | OpenClaw, an autonomous AI agent you run yourself: web dashboard, scheduled tasks, plugins, persistent workspace. This template uses the coollabsio al... |
| **OpenFaaS** | `func` | games | `9993` | Serverless functions made simple |
| **Opengist** | `opengist` | development | `6157` | Pastebin built on Git, like GitHub Gist: every snippet is a repo you can clone, push to and fork, with syntax highlighting, Markdown, embeds, search, ... |
| **OpenList** | `openlist` | development, data, games | `8080` | File list that puts your cloud drives and storage behind one web UI and WebDAV server, from OneDrive, Google Drive, Dropbox and S3 to SMB, FTP and loc... |
| **OpenObserve** | `openobserve` | data, monitoring | `5000` | OpenObserve - logs, metrics, and traces in a single Rust binary: the open-source Datadog/Splunk/Elasticsearch alternative. |
| **Openshot** | `openshot` | media, development | `3000` | [OpenShot](https://openshot.org/) Video Editor is an award-winning free and open-source video editor for Linux, Mac, and Windows, and is dedicated to ... |
| **Openssh-server** | `openssh-server` | development, games | `2222` | [Openssh-server](https://www.openssh.com/) is a sandboxed environment that allows ssh access without giving keys to the entire server. Giving ssh acce... |
| **OpenTodo** | `opentodo` | development, productivity, data | `8080` | Open-source, local-first task manager. Works offline and syncs every device from one small container. Source: https://github.com/OpenTodoApp/OpenTodo |
| **OpenVPN Access Server** | `openvpn-as` | security, network, games | `943` | OpenVPN Access Server is a full featured secure network tunneling VPN software solution that integrates OpenVPN server capabilities, enterprise manage... |
| **Opera** | `opera` | development | `3000` | [Opera](https://www.opera.com/) is a multi-platform web browser developed by its namesake company Opera. The browser is based on Chromium, but disting... |
| **OpnForm** | `opnform` | development, productivity | `8380` | OpnForm is an open-source form builder. It's an alternative to products like Typeform, JotForm, Tally etc. |
| **Oracle Database Free** | `oracle` | development, data, finance | `1521` | Oracle Database Free (the 26ai line) - the actual Oracle Database, free for development AND production under the Oracle Free Use Terms and Conditions,... |
| **Orcaslicer** | `orcaslicer` | development | `3000` | [Orca Slicer](https://github.com/SoftFever/OrcaSlicer) is an open source slicer for FDM printers. OrcaSlicer is fork of Bambu Studio, it was previousl... |
| **Organizr** | `organizr` | utilities | `9983` | Organizr self-hosted application for Runtipi. |
| **Organizr (container)** | `organizr-v2` | games | `80` | Organizr allows you to setup Tabs that will be loaded all in one webpage. You can then work on your server with ease. |
| **Ory Kratos (Oathkeeper)** | `ory-kratos-oathkeeper` | security, network, development | `8080` | Ory Kratos with Oathkeeper (ORY Oathkeeper is an Identity & Access Proxy (IAP) and Access Control Decision API that authorizes HTTP requests based on ... |
| **Ory Kratos (Standalone)** | `ory-kratos` | security, network, development | `4455` | Ory Kratos with Oathkeeper is _the_ developer-friendly, security-hardened and battle-test Identity, User Management and Authentication system for the ... |
| **Ory Kratos Standalone** | `ory-kratos-standalone` | utilities | `4455` | Ory Kratos Standalone self-hosted application for Runtipi. |
| **Oscam** | `oscam` | media, development, data | `8888` | [Oscam](https://git.streamboard.tv/common/oscam) is an Open Source Conditional Access Module software used for descrambling DVB transmissions using sm... |
| **Outline** | `outline` | development, productivity, social | `3000` | Open source collaborative knowledge base for modern teams. Source: https://github.com/outline/outline |
| **Overseerr (container)** | `overseerr` | media, development, data | `5055` | Overseerr is a request management and media discovery tool built to work with your existing Plex ecosystem. |
| **Owncast** | `owncast` | media, development, social | `5000` | Owncast - your own self-hosted live streaming server: a Twitch / YouTube Live alternative with a built-in web video player, live chat, and federation. |
| **Owncloud** | `owncloud` | development, productivity, data | `8080` | ownCloud is a self-hosted file sync and share server. It provides access to your data through a web interface, sync clients or WebDAV while providing ... |
| **PairDrop** | `pairdrop` | network, development, productivity | `3000` | Local file sharing in your browser, inspired by Apple's AirDrop. Source: https://github.com/schlagmichdoch/PairDrop |
| **Paperless Ngx** | `paperless-ngx` | productivity | `5000` | Paperless Ngx self-hosted application for Runtipi. |
| **Papra** | `papra` | development, productivity | `8080` | Document archive for receipts, contracts, payslips and all the other paperwork you need to keep: upload them, search their text (scans included), and ... |
| **Parseable** | `parseable` | development, data, monitoring | `5000` | Parseable - a single-binary log lake built for object storage: ingest logs over HTTP, store them as compressed Parquet on S3, query with SQL. Rust, le... |
| **Passky Client** | `passky-client` | security | `8081` | Passky is a simple, modern, lightweight, open-source and secure password manager. |
| **Passky Server** | `passky-server` | security, games | `8080` | Passky is a simple, modern, lightweight, open-source and secure password manager. |
| **Password Pusher** | `password-pusher` | security, development, data | `8080` | Share passwords, text, files and links as a link that expires after a set number of views or days, so they don't sit in someone's chat history or inbo... |
| **Pcsx2** | `pcsx2` | games | `3000` | [PCSX2](https://pcsx2.net/) is an open source PS2 Emulator. |
| **Pelorus** | `pelorus` | development, games | `3001` | [Pelorus](https://github.com/linuxserver/pelorus) is an AI navigator for Selkies-powered Linux desktops. Pelorus runs a FastAPI server that gives an L... |
| **Penpot** | `penpot` | development | `8080` | Penpot - the open-source design and prototyping platform (the Figma alternative): SVG-native, web-based, with real design-to-dev handoff. MPL-2.0. Fro... |
| **Percona Server** | `percona-server` | development, data, games | `3306` | Percona Server for MySQL - a free, fully MySQL-compatible drop-in with extra instrumentation (detailed `INFORMATION_SCHEMA` and `PERFORMANCE_SCHEMA` t... |
| **Percona XtraDB Cluster** | `percona-xtradb-cluster` | development, data | `3306` | Percona XtraDB Cluster - synchronous, multi-primary MySQL high availability built on Galera. |
| **Petio** | `petio` | media, games | `7777` | Petio is a third party companion app available to Plex server owners to allow their users to request, review and discover content. |
| **pgAdmin** | `pgadmin` | development, data, games | `5050` | PGAdmin is a web-based GUI tool used to interact with the Postgres database sessions, both locally and remote servers as well. You can use PGAdmin to ... |
| **Phoenix** | `phoenix` | development, data | `5000` | Phoenix - LLM tracing, evaluations, datasets, and a prompt playground in ONE container, OpenTelemetry-native. |
| **Photoprism** | `photoprism` | media | `2342` | PhotoPrism is an AI-powered app for browsing, organizing & sharing your photo collection. It makes use of the latest technologies to tag and find pict... |
| **PhotoShow** | `photoshow` | media | `80` | A simple, easy way to turn a photo album into a webgallery. |
| **Phpmyadmin** | `phpmyadmin` | development, data | `80` | [Phpmyadmin](https://github.com/phpmyadmin/phpmyadmin/) is a free software tool written in PHP, intended to handle the administration of MySQL over th... |
| **Pi-Hole** | `pihole` | security, network | `53` | A Linux network-level advertisement and Internet tracker blocking application which acts as a DNS sinkhole. |
| **Pi-Hole DoH/DoT** | `pihole-doh-dot` | security, network | `53` | A Linux network-level advertisement and Internet tracker blocking application which acts as a DNS sinkhole with both DoH (DNS over HTTPS) and DoT (DNS... |
| **Pi-Hole-Unbound** | `pihole-unbound` | security, network, development | `53` | A Linux network-level advertisement and Internet tracker blocking application which acts as a DNS sinkhole. This version has Ubound software installed... |
| **Pi.alert** | `pi-alert` | network, monitoring | `20211` | WIFI / LAN intruder detector |
| **PicoShare** | `picoshare` | development, data | `8080` | Minimalist file sharing: upload any file and get a direct link to it, with no re-encoding, no size limit and an optional expiry date. Guest links let ... |
| **Pidgin** | `pidgin` | network, social | `3000` | [Pidgin](https://pidgin.im/) is a chat program which lets you log into accounts on multiple chat networks simultaneously. This means that you can be c... |
| **Pinchflat** | `pinchflat` | media | `8945` | Your next YouTube media manager |
| **Pingvin** | `pingvin-share` | utilities | `3123` | Pingvin Share is self-hosted file sharing platform and an alternative for WeTransfer. |
| **Pingvin** | `pingvin` | utilities | `3123` | Pingvin self-hosted application for Runtipi. |
| **Piper** | `piper` | development, games | `10200` | [Piper](https://github.com/rhasspy/wyoming-piper) is a fast, local neural text to speech system that sounds great and is optimized for the Raspberry P... |
| **Piwigo** | `piwigo` | media | `80` | [Piwigo](http://piwigo.org/) is a photo gallery software for the web that comes with powerful features to publish and manage your collection of pictur... |
| **Pixel-server** | `pixel-server` | games | `85` | Wireless control of PixelStrips or NeoPixels using a web graphical interface running on a Raspberry Pi. |
| **Plane** | `plane` | development, productivity | `8080` | Project management tool from the future. An open-source software development tool to manage issues, sprints, and product roadmaps with peace of mind. |
| **Planka (container)** | `planka` | development, productivity | `1337` | [Planka](https://github.com/plankanban/planka/) is an elegant open source project tracking tool. |
| **PlantUML Server** | `plantuml-server` | development, productivity, games | `8380` | Web editor and rendering server for PlantUML, turning plain-text descriptions into sequence, class, component and other diagrams as PNG, SVG or ASCII,... |
| **Plausible** | `plausible` | security, data, monitoring | `5000` | Plausible - privacy-friendly web analytics: a lightweight, cookie-free, open-source Google Analytics alternative. A clean single-page dashboard, no pe... |
| **Plesk** | `plesk` | utilities | `21` | WebOps platform and hosting control panel |
| **Plex** | `plex` | media, development, games | `80` | [Plex](https://plex.tv) organizes video, music and photos from personal media libraries and streams them to smart TVs, streaming boxes and mobile devi... |
| **Plex Requests** | `plexrequests` | media, development, data | `3000` | Simple automated way for users to request new content for Plex. |
| **PlexTraktSync** | `plextraktsync` | media, productivity, data | `9993` | A python script that syncs the movies, shows and ratings between trakt and Plex |
| **Plone** | `plone` | utilities | `8080` | A free and open-source CMS built on top of Zope |
| **PocketBase** | `pocketbase` | security, development, data | `5000` | Pocketbase, an entire backend (SQLite, auth, realtime subscriptions, file storage, admin UI) in one container. The simplest template in the catalogue:... |
| **PodFetch** | `podfetch` | media, development, data | `8000` | Sleek, self-hosted podcast manager that automatically downloads new episodes, offers a web UI for listening, and provides a GPodder-compatible sync AP... |
| **Portainer Agent** | `portainer-agent` | utilities | `8080` | Manage all the resources in your Swarm cluster |
| **Poste.io** | `poste-io` | productivity, games | `82` | Full stack mailserver solution with TLS support. POP3s, SMTP(s), IMAPs, RSPAMD, Clamav, Roundcube(HTTPS), SPF, DKIM with simple installation and web a... |
| **Posteio** | `posteio` | utilities | `82` | Posteio self-hosted application for Runtipi. |
| **PostgreSQL** | `postgresql` | development, data | `5432` | The most advanced open-source database |
| **Postiz** | `postiz` | media, development, social | `5000` | An alternative to: Buffer.com, Hypefury, Twitter Hunter, etc...Postiz offers everything you need to manage your social media posts,build an audience, ... |
| **Ppsspp** | `ppsspp` | games | `3000` | [PPSSPP](https://www.ppsspp.org/) is a free and open-source PSP emulator for Windows, macOS, Linux, iOS, Android, Nintendo Wii U, Nintendo Switch, Bla... |
| **Prefect** | `prefect` | development, automation, games | `5000` | Prefect 3 - workflow orchestration for Python people: flows are decorated functions, deployments schedule them, and the UI shows every run. The server... |
| **PrestaShop** | `prestashop` | utilities | `5000` | PrestaShop 9 - the open-source storefront that runs a huge share of European e-commerce: catalogue, checkout, multi-language/multi-currency, and a vas... |
| **PriceGhost** | `priceghost` | social | `5432` | A self-hosted price tracking application that monitors product prices from any website.Get notified when prices drop, hit your target price, or items ... |
| **PrivateBin** | `privatebin` | productivity, data, games | `8080` | PrivateBin is a minimalist, open source online pastebin where the server has zero knowledge of pasted data! |
| **Pro Mosquitto with Management Center** | `pro-mosquitto-with-management-center` | development, automation | `9993` | Commercial-grade Mosquitto MQTT broker with Management Center |
| **Projectsend** | `projectsend` | development, productivity, data | `80` | [Projectsend](http://www.projectsend.org) is a self-hosted application that lets you upload files and assign them to specific clients that you create ... |
| **ProtonMail Bridge** | `protonmail-bridge` | development, productivity | `143` | This is an unofficial Docker container of the ProtonMail Bridge. Some of the scripts are based on Hendrik Meyer's work. |
| **Prowlarr** | `prowlarr` | media, network, development | `9696` | [Prowlarr](https://github.com/Prowlarr/Prowlarr) is a indexer manager/proxy built on the popular arr .net/reactjs base stack to integrate with your va... |
| **ProxiTok** | `proxitok` | development, social | `8080` | Use Tiktok with an alternative frontend, inspired by Nitter. |
| **Pumperly** | `pumperly` | network, development | `3000` | Open-source fuel and EV route planner with live prices from 22 countries. Source: https://github.com/GeiserX/Pumperly |
| **Pure-FTP Server** | `pureftp` | games | `21` | Pure-FTPd is a free (BSD), secure, production-quality and standard-conformant FTP server. |
| **pve-exporter** | `pve-exporter` | monitoring | `9221` | This is an exporter that exposes information gathered from Proxmox VE node for use by the Prometheus monitoring system. |
| **Pwndrop** | `pwndrop` | security, development, data | `8080` | [Pwndrop](https://github.com/kgretzky/pwndrop) is a self-deployable file hosting service for sending out red teaming payloads or securely sharing your... |
| **Pycharm** | `pycharm` | development, data | `3000` | [PyCharm](https://www.jetbrains.com/pycharm/) offers out-of-the-box support for Python, databases, Jupyter, Git, Conda, PyTorch, TensorFlow, Hugging F... |
| **Pydio** | `pydio` | security, development, data | `443` | Pydio (formerly AjaXplorer) is a mature open source software solution for file sharing and synchronization. With intuitive user interfaces (web / mobi... |
| **Pydio-cells** | `pydio-cells` | productivity | `8080` | [Pydio-cells](https://pydio.com/) is the nextgen file sharing platform for organizations. It is a full rewrite of the Pydio project using the Go langu... |
| **Pyload-ng** | `pyload-ng` | data | `8000` | [pyLoad](https://pyload.net/) is a Free and Open Source download manager written in Python and designed to be extremely lightweight, easily extensible... |
| **Qbittorrent** | `qbittorrent` | data | `8080` | The [Qbittorrent](https://www.qbittorrent.org/) is a bittorrent client programmed in C++ / Qt that uses libtorrent (sometimes called libtorrent-raster... |
| **Qdirstat** | `qdirstat` | security, development, data | `3000` | [QDirStat](https://github.com/shundhammer/qdirstat) Qt-based directory statistics: KDirStat without any KDE -- from the author of the original KDirSta... |
| **Qdrant** | `qdrant` | network, development, productivity | `6333` | Qdrant vector database, single container + volume, internal-only by default (no API key is configured; the project network is the boundary). |
| **Qemu-static** | `qemu-static` | development, productivity, games | `80` | # This container needs special attention. Please check https://hub.docker.com/r/linuxserver/qemu-static for details. |
| **qFlood** | `qflood` | security, development, productivity | `3000` | A docker image with qBittorrent and the Flood UI, also optional WireGuard VPN support. See the official documentation for WireGuard VPN support at htt... |
| **Quassel IRC** | `quassel-core` | social | `4242` | Quassel IRC is a modern, cross-platform, distributed IRC client, meaning that one (or multiple) client(s) can attach to and detach from a central core... |
| **RabbitMQ (container)** | `rabbitmq-container` | social | `5671` | Highly reliable enterprise messaging system |
| **RabbitMQ (stack)** | `rabbitmq` | media, productivity, social | `5000` | 3-node RabbitMQ 4.x cluster (quorum-queue ready), deployable locally with plain Docker Compose or to Miget as a compose stack. |
| **Rackula** | `rackula` | network, development | `8383` | Plan your rack layout. Drag your devices in, move them around, export it. It runs in your browser. You can close the tab whenever you want |
| **Radarr** | `radarr` | media, development | `7878` | [Radarr](https://github.com/Radarr/Radarr) - A fork of Sonarr to work with movies à la Couchpotato. |
| **Raneto** | `raneto` | data | `3000` | [Raneto](http://raneto.com/) - is an open source Knowledgebase platform that uses static Markdown files to power your Knowledgebase. |
| **Rawtherapee** | `rawtherapee` | development | `3000` | [RawTherapee](https://rawtherapee.com/) is a free, cross-platform raw image processing program! |
| **Rclone Config Backup** | `rclone` | development, data | `8080` | Rclone is a command line program to sync files and directories to and from cloud providers (Dropbox, GDrive, Box, etc) |
| **Reach Me Out** | `reach-me-out` | development, data | `8080` | Static, config-driven link-in-bio page. Profile card, tappable links, vCard download, QR share — all driven from a single YAML file baked at build tim... |
| **Reactive-Resume** | `reactive-resume` | data | `80` | A one-of-a-kind resume builder that's not out to get your data. Completely secure, customizable, portable, open-source and free forever. |
| **Readarr (container)** | `readarr` | media, data, automation | `8787` | Readarr - Book Manager and Automation (Sonarr for Ebooks) |
| **Readeck** | `readeck` | media, development, productivity | `8097` | Read-it-later app that saves the full text and images of web pages, with highlights, labels, collections, full-text search and e-book export. Source: ... |
| **Redis (container)** | `redis-container` | development, data | `6379` | Open-source in-memory data structure store |
| **Redis (stack)** | `redis` | security, development, data | `6379` | Redis - the in-memory data store used for caching, queues, pub/sub, streams, rate-limiting, and rich data structures. This is a single node, password-... |
| **Redis Cluster (stack)** | `redis-cluster` | development | `8080` | Redis Cluster - horizontally-scaled Redis where the keyspace is partitioned across multiple master shards, each with a replica. This template runs 6 n... |
| **Redis Cluster (swarm)** | `redis-cluster-swarm` | development, data | `8080` | Open-source in-memory data structure store - Cluster mode |
| **Redis Sentinel** | `redis-sentinel` | development | `8080` | Redis Sentinel - high availability for Redis with automatic failover. This template runs one master, two replicas, and three sentinels that watch the ... |
| **Redmine** | `redmine` | productivity | `3000` | Open-source project management tool |
| **Redpanda** | `redpanda` | media, productivity, social | `5000` | 3-broker Redpanda cluster (Kafka-compatible, no ZooKeeper/JVM) with Redpanda Console, deployable locally with plain Docker Compose or to Miget as a co... |
| **Registry** | `registry` | productivity | `5000` | Docker image registry |
| **Registry (cache)** | `registry-cache` | productivity | `5000` | Docker image registry configured as a DockerHub pull through cache |
| **Remmina** | `remmina` | network | `3000` | [Remmina](https://remmina.org/) is a remote desktop client written in GTK, aiming to be useful for system administrators and travellers, who need to w... |
| **Remotely** | `remotely` | utilities | `5009` | Remotely is a remote control and remote scripting solution, built with .NET 6, Blazor, and SignalR Core. |
| **ReplayHaven** | `replayhaven` | media, development, games | `5000` | Game clip archive: a Windows client names every clip with a local AI, this server keeps the originals and streams them to your devices. Source: https:... |
| **Resilio-sync** | `resilio-sync` | development, data | `8888` | [Resilio-sync](https://www.resilio.com/individuals/) (formerly BitTorrent Sync) uses the BitTorrent protocol to sync files and folders between all of ... |
| **Retroarch** | `retroarch` | media, development, games | `3000` | [RetroArch](https://retroarch.com/) is a frontend for emulators, game engines and media players. It enables you to run classic games on a wide range o... |
| **Reveal.js** | `revealjs` | utilities | `6060` | It is an open source HTML presentation framework. It enables anyone with a web browser to create fully featured and beautiful presentations for free -... |
| **Rocket.Chat** | `rocketchat` | media, development, productivity | `5000` | Rocket.Chat - the open-source team communication platform: channels, DMs, threads, voice/video, an apps marketplace, and omnichannel (livechat/email/s... |
| **RomM** | `romm` | utilities | `480` | A beautiful, powerful, self-hosted rom manager. |
| **Roundcube** | `roundcube` | productivity | `80` | Roundcube - the standard open-source webmail client: folders, search, contacts, filters, and a clean responsive skin. |
| **Rpcs3** | `rpcs3` | data, games | `3000` | [RPCS3](https://rpcs3.net/) is a multi-platform open-source Sony PlayStation 3 emulator and debugger written in C++ for Windows, Linux, macOS and Free... |
| **Rport** | `rport` | utilities | `3000` | RPort is free remote access and remote management, now acquired by RealVNC |
| **Rr_Mtm** | `rr-mtm` | utilities | `8080` | Rr_Mtm self-hosted application for Runtipi. |
| **Rsnapshot** | `rsnapshot` | development, data | `80` | [Rsnapshot](http://www.rsnapshot.org/) is a filesystem snapshot utility based on rsync. rsnapshot makes it easy to make periodic snapshots of local ma... |
| **RSSHub** | `rsshub` | development, social | `1200` | RSS feed maker for thousands of sites that don't have a feed of their own, like GitHub issues, news sites, forums and shops. Source: https://github.co... |
| **Rust Desk (stack)** | `rust-desk` | utilities | `21115` | Rust Desk is an Open source virtual or remote desktop infrastructure for everyone! |
| **Rustdesk (container)** | `rustdesk` | security | `3000` | [RustDesk](https://rustdesk.com/) is a full-featured open source remote control alternative for self-hosting and security with minimal configuration. |
| **RustFS** | `rustfs` | development, data | `8080` | S3-compatible object storage written in Rust, an open-source alternative to MinIO, with a web console for browsing buckets and managing users, policie... |
| **ruTorrent** | `rutorrent` | data | `6881` | Popular torrent client with a webui for ease of use. |
| **Ryot** | `ryot` | media, development, productivity | `8080` | Tracker for the films, shows, books, anime, music and podcasts you get through, plus your workouts: progress, ratings, reviews and stats in one place,... |
| **Sabnzbd** | `sabnzbd` | data | `8080` | [Sabnzbd](http://sabnzbd.org/) makes Usenet as simple and streamlined as possible by automating everything we can. All you have to do is add an .nzb. ... |
| **Saleor** | `saleor` | development, monitoring | `8000` | Saleor - headless, GraphQL-first e-commerce (BSD-3): the API your custom storefront talks to, with a polished dashboard for the team. Official images,... |
| **Samba** | `samba` | development | `139` | Samba has provided secure, stable and fast file and print services for all clients using the SMB/CIFS protocol, such as all versions of DOS and Window... |
| **Scality S3** | `scality-s3` | data, games | `8000` | Standalone AWS S3 protocol server |
| **Scrutiny** | `scrutiny` | monitoring | `8080` | WebUI for smartd S.M.A.R.T monitoring |
| **Scummvm** | `scummvm` | security, development, data | `3000` | [ScummVM](https://www.scummvm.org/) is a program which allows you to run certain classic graphical adventure and role-playing games, provided you alre... |
| **Sealskin** | `sealskin` | media, development, productivity | `8443` | [Sealskin](https://github.com/selkies-project/sealskin/) is a self-hosted browser isolation and remote application streaming platform. It runs desktop... |
| **SearXNG (container)** | `searxng` | security | `9017` | Open-Source Privacy-respecting metasearch engine |
| **Seawise.io Client** | `seawise-io-client` | network | `9993` | Share self-hosted apps with family and friends, no port forwarding. Client for the Seawise.io service (free account required). |
| **Seerr** | `seerr` | media, development | `5055` | Request manager for Jellyfin, Plex and Emby, where people ask for films and shows and Sonarr and Radarr fetch them. It's the merged successor to Overs... |
| **Sematext Docker Agent (container)** | `sematext-agent` | productivity, monitoring | `8080` | Collect logs, metrics and docker events |
| **Sematext Docker Agent (swarm)** | `sematext-docker-agent-swarm` | productivity, monitoring | `8080` | Collect logs, metrics and docker events |
| **SFTPGo** | `sftpgo` | development, data | `5000` | SFTPGo - the upload portal for Miget Buckets: create users whose storage IS an S3 bucket (custom endpoint, path-style, optional key prefix per user), ... |
| **Shaarli** | `shaarli` | media, development, data | `7755` | The personal, minimalist, super fast, database-free, bookmarking service. |
| **Shadowbroker** | `shadowbroker` | utilities | `3000` | Global Threat Intercept — Real-Time Geospatial Intelligence Platform |
| **Shadps4** | `shadps4` | games | `3000` | [shadPS4](https://shadps4.net/) is an early PlayStation 4 emulator for Windows, Linux and macOS written in C++. |
| **Shiori (container)** | `shiori` | media | `7564` | Shiori is a simple bookmarks manager written in Go language. Intended as a simple clone of Pocket. You can use it as command line application or as we... |
| **Shlink** | `shlink` | development, data | `5000` | Shlink - a self-hosted URL shortener: short links on your own domain with a full REST API, QR codes, rich visit analytics (with optional GeoIP), tags,... |
| **Shotcut** | `shotcut` | media, development | `3000` | [Shotcut](https://www.shotcut.org/) is a free, open source, cross-platform video editor. |
| **SickChill** | `sickchill` | media, development, data | `8081` | Automatic Video Library Manager for TV Shows. It watches for new episodes of your favorite shows, and when they are posted it does its magic. |
| **Sickgear** | `sickgear` | media, development, data | `8081` | [SickGear](https://github.com/sickgear/sickgear) provides management of TV shows and/or Anime, it detects new episodes, links downloader apps, and mor... |
| **SickRage** | `sickrage` | media, development, data | `8081` | Automatic Video Library Manager for TV Shows. It watches for new episodes of your favorite shows, and when they are posted it does its magic. |
| **Signal** | `signal` | security, social | `3000` | [Signal](https://signal.org/) is a messaging app with privacy at its core. It is free and easy to use, with strong end-to-end encryption that keeps yo... |
| **SilverBullet** | `silverbullet` | development, productivity | `3300` | Notes app for Markdown pages you can program, with two-way links, tasks, queries over everything you've written and Lua scripting for your own command... |
| **Silverstripe** | `silverstripe` | utilities | `8080` | Silverstripe CMS is a free and open source Content Management System (CMS) and Framework for creating and maintaining websites and web applications. |
| **SiYuan** | `siyuan` | development, productivity | `8080` | Note-taking app built from blocks, so any paragraph can be linked, embedded or queried from anywhere else. Markdown, backlinks, a graph view and daily... |
| **Smokeping** | `smokeping` | network, development, monitoring | `80` | [Smokeping](https://oss.oetiker.ch/smokeping/) keeps track of your network latency. For a full example of what this application is capable of visit [U... |
| **Snibox (container)** | `snibox` | utilities | `3010` | Self-hosted snippet manager. |
| **Snipe-IT** | `snipe-it` | development, productivity | `8080` | IT asset manager for keeping track of laptops, licences, accessories and consumables: who has what, check-outs and check-ins, audits, maintenance, dep... |
| **Snippet Box (stack)** | `snippet-box` | development | `5000` | Snippet Box is a simple self-hosted app for organizing your code snippets. It allows you to easily create, edit, browse and manage your snippets in va... |
| **Snippetbox** | `snippetbox` | utilities | `5000` | Snippetbox self-hosted application for Runtipi. |
| **Socket-proxy** | `socket-proxy` | network, development, productivity | `80` | # This container needs special attention. Please check https://hub.docker.com/r/linuxserver/socket-proxy for details. |
| **Softing SDEX Suite** | `softing-sdex-suite` | development, data, automation | `9993` | Connect PLCs and CNCs from multiple manufacturers and provide their industrial data to IT applications via OPC UA and MQTT. |
| **SolidPing** | `solidping` | security, network, development | `4000` | Uptime and synthetic monitoring with status pages, incidents and alerts. Checks HTTP, DNS, TCP, ICMP, TLS expiry, databases, message brokers, heartbea... |
| **SolidTime** | `solidtime` | utilities | `8080` | The modern Open-Source Time Tracker |
| **Solr** | `solr` | utilities | `8983` | Open-source enterprise search platform |
| **Sonarr** | `sonarr` | media, data, social | `8989` | [Sonarr](https://sonarr.tv/) (formerly NZBdrone) is a PVR for usenet and bittorrent users. It can monitor multiple RSS feeds for new episodes of your ... |
| **SORBA SDE** | `sorba-sde` | network, development, data | `9993` | The SORBA Smart Data Engine (SDE) is an industrial data collection/gateway device capable of Advanced Edge Analytics & Machine Learning Edge Processin... |
| **SparkyFitness** | `sparkyfitness` | development, productivity, data | `8080` | Fitness tracker for food, exercise, water, sleep, fasting, mood and body measurements, with goals, long-term reports and family sharing, plus sync fro... |
| **Speedtest Tracker (stack)** | `speedtest-tracker` | network, development | `8288` | Speedtest Tracker is a self-hosted internet performance tracking application that runs speedtest checks against Ookla's Speedtest service. Source: htt... |
| **Spliit** | `spliit` | development, finance | `8080` | Expense splitter for trips, flatmates and nights out, tracking who paid for what in a shared group and working out who owes who, with no accounts need... |
| **Spoolman** | `spoolman` | development | `7912` | 3D printer filament tracker that keeps count of your spools, what's left on each and where they live, makes printable QR labels, and takes usage strai... |
| **Spotube** | `spotube` | media, development, data | `3000` | [Spotube](https://spotube.krtirtho.dev/) is an open source, cross-platform Spotify client compatible across multiple platforms utilizing Spotify's dat... |
| **SQL Server (container)** | `sql-server-container` | development, data, games | `1433` | Microsoft SQL Server Developer for Windows containers |
| **SQL Server (stack)** | `mssql` | development, data, games | `1433` | Official SQL Server on Linux container (SQL Server 2025), Express edition by default - the edition Microsoft licenses for production at no cost. Singl... |
| **SQL Server Express** | `sql-server-express` | development, data, games | `1433` | Microsoft SQL Server Express for Windows containers |
| **Sqlitebrowser** | `sqlitebrowser` | development, data | `3000` | [DB Browser for SQLite](https://sqlitebrowser.org/) is a high quality, visual, open source tool to create, design, and edit database files compatible ... |
| **Sshwifty** | `sshwifty` | development, games | `8182` | Sshwifty is a SSH and Telnet connector made for the Web. It can be deployed on your computer or server to provide SSH and Telnet access interface for ... |
| **Stalwart Mail Server** | `stalwart-mail` | network, development, productivity | `8080` | All-in-one mail server supporting SMTP, IMAP, JMAP, and more, with a built-in web administration interface. Source: https://github.com/stalwartlabs/st... |
| **Statping** | `statping` | network, monitoring | `4040` | An easy to use Status Page for your websites and applications. Statping will automatically fetch the application and render a beautiful status page wi... |
| **Steam** | `steam` | games | `3000` | [Steam](https://store.steampowered.com/) is the ultimate destination for playing, discussing, and creating games. |
| **Stirling PDF {shmolf}** | `stirling-pdf` | utilities | `5417` | Your locally hosted one-stop-shop for all your PDF needs. |
| **Stump** | `stump` | media, development, games | `10801` | A free and open source comics, manga, and digital book server with OPDS support. Source: https://github.com/stumpapp/stump |
| **Supabase** | `supabase` | security, network, development | `3000` | The full Supabase stack, Postgres (supabase image with extensions), Auth (GoTrue), REST (PostgREST), Realtime, Storage, postgres-meta, Studio, behind ... |
| **Supabase Lite** | `supabase-lite` | security, network, development | `3000` | The budget cut of the supabase template: Postgres, Auth (GoTrue) and REST (PostgREST) behind the Kong gateway - the four services most Supabase apps a... |
| **Supabase Nano** | `supabase-nano` | security, development, monitoring | `3000` | supabase-lite squeezed into a 1 GiB plan - the same six services (Postgres, Auth, REST, Kong, Studio, postgres-meta), memory- tuned until the whole st... |
| **Supabase Pico** | `supabase-pico` | security, development | `5000` | Supabase's API surface - Postgres, Auth (GoTrue) and REST (PostgREST) - in 512 MiB total. |
| **Super Productivity** | `super-productivity` | development, productivity | `8095` | To-do list with timeboxing and time tracking built in, and it can pull in issues from Jira, GitHub and GitLab. Source: https://github.com/super-produc... |
| **Superset** | `superset` | development, data, monitoring | `5000` | Superset - the Apache BI platform: dashboards, the no-code chart builder, SQL Lab, and alerts/reports, over practically every database. |
| **SurrealDB** | `surrealdb` | development, data, games | `8020` | SurrealDB is an end-to-end cloud native database for web, mobile, serverless, jamstack, backend, and traditional applications. |
| **Swag** | `swag` | security, network, games | `443` | SWAG - Secure Web Application Gateway (formerly known as letsencrypt, no relation to Let's Encrypt™) sets up an Nginx webserver and reverse proxy with... |
| **Swarm monitoring** | `swarm-monitoring` | monitoring | `9993` | Monitor your cluster performances with Prometheus & Grafana |
| **Synclounge** | `synclounge` | media, development, data | `8088` | [Synclounge](https://github.com/samcm/synclounge) is a third party tool that allows you to watch Plex in sync with your friends/family, wherever you a... |
| **Syncthing (container)** | `syncthing` | data | `8384` | [Syncthing](https://syncthing.net) replaces proprietary sync and cloud services with something open, trustworthy and decentralized. Your data is your ... |
| **Syslog-ng** | `syslog-ng` | monitoring | `514` | [syslog-ng](https://www.syslog-ng.com/products/open-source-log-management/) allows you to flexibly collect, parse, classify, rewrite and correlate log... |
| **System Stats OLED display** | `oled-stats` | utilities | `8080` | A quick way to display system stats on a 128x64 I2C OLED display. |
| **systemprompt** | `systemprompt` | network, development | `8080` | Self-owned AI control plane: governance gateway for Claude, OpenAI, and Gemini with policy checks, audit, rate limits, and MCP orchestration. Bundles ... |
| **Tabby** | `tabby` | development, productivity | `8010` | Tabby is an infinitely customizable cross-platform terminal app for local shells, serial, SSH and Telnet connections. |
| **Tailscale (container)** | `tailscale` | security, network, development | `8080` | Connect your devices and users together in your own secure Zero config virtual private network. |
| **Tandoor** | `tandoor` | development | `82` | The recipe manager that allows you to manage your ever growing collection of digital recipes. |
| **Tautulli** | `tautulli` | media, data, monitoring | `8181` | [Tautulli](http://tautulli.com) is a python based web application for monitoring, analytics and notifications for Plex Media Server. |
| **Tdarr** | `tdarr` | media | `8265` | Tdarr is a popular conditional transcoding application for processing large (or small) media libraries. |
| **Teable** | `teable` | media, development, productivity | `8080` | Spreadsheet-style database in the vein of Airtable, built on Postgres: grid, kanban, calendar, gallery and form views, file attachments, formulas, rea... |
| **Technitium DNS** | `technitium-dns` | security, network, development | `5380` | An open source authoritative and recursive DNS server with a web console for management. Source: https://github.com/TechnitiumSoftware/DnsServer |
| **TEI Embeddings** | `tei` | development, games | `5000` | TEI - Hugging Face's Rust embeddings server: small models like `BAAI/bge-small-en-v1.5` (384-dim) serve real RAG workloads from CPU in ~512 MB, over b... |
| **tela** | `tela` | development, productivity, data | `8080` | Self-hostable, markdown-native team wiki: Go + PostgreSQL backend, a React editor with live Yjs collaboration, full-text + optional semantic search, W... |
| **Telegram** | `telegram` | data, social | `3000` | [Telegram](https://telegram.org/) is a cloud-based mobile and desktop messaging app. |
| **Teleport** | `teleport` | security, development, data | `3080` | Teleport allows engineers and security professionals to unify access for SSH servers, Kubernetes clusters, web applications, and databases across all ... |
| **Temporal** | `temporal` | development, automation | `8080` | Temporal - durable execution: write workflows as ordinary code and Temporal makes them crash-proof, with automatic retries, timers that survive restar... |
| **Termix** | `termix` | network, development, games | `8080` | SSH terminal and server manager in the browser, with saved hosts, tunnels and a file editor. Source: https://github.com/Termix-SSH/Termix |
| **Terraria Server** | `terraria-server` | development, productivity, games | `7779` | Dedicated Terraria server in a Docker container. Source: https://github.com/hexlo/terraria-server-docker |
| **Thelounge** | `thelounge` | development, social, games | `9000` | [Thelounge](https://thelounge.github.io/) (a fork of shoutIRC) is a web IRC client that you host on your own server. |
| **Thunderbird** | `thunderbird` | media, productivity, social | `3000` | [Thunderbird](https://www.thunderbird.net/) is a free and open-source personal information manager primarily used as an e-mail client with a calendar ... |
| **TiddlyWiki** | `tiddlywiki` | media, productivity | `8080` | A unique, non-linear notebook wiki. |
| **Timescale DB** | `timescale-db` | development, data | `9993` | Open-source time series database developed by Timescale Inc |
| **Timescaledb** | `timescaledb` | utilities | `5432` | Timescaledb self-hosted application for Runtipi. |
| **TimeTagger** | `timetagger` | productivity | `280` | Open source time-tracker with an interactive user experience and powerful reporting. |
| **Tiny Tiny RSS** | `tt-rss` | social | `80` | Tiny Tiny RSS is an open source web-based news feed (RSS/Atom) reader and aggregator, designed to allow you to read news from any location, while feel... |
| **TinyMediaManager** | `tinymediamanager` | media, development, data | `5900` | TinyMediaManager is a media management tool written in Java/Swing. It is written to provide metadata for the Kodi Media Center (formerly known as XBMC... |
| **Tolgee** | `tolgee` | development, productivity, data | `8080` | Localisation platform for translating your app's strings, with in-context editing, machine translation, screenshots, comments, import and export in mo... |
| **Tooljet** | `tooljet` | development | `8080` | Tooljet is an Open-source low-code application development platform for building and deploying business applications. |
| **TOSIBOX Lock for Container** | `tosibox-lock-for-container` | development, automation | `9993` | Lock for Container brings secure connectivity inside your industrial IoT devices |
| **Traefik (container)** | `traefik` | security, network, development | `80` | Cloud-Native Networking Stack That Just Works. Source: https://github.com/traefik/traefik |
| **Traggo** | `traggo` | productivity | `3030` | Traggo is a tag-based time tracking tool. In Traggo there are no tasks, only tagged time spans. |
| **Transmission** | `transmission` | data | `9091` | [Transmission](https://www.transmissionbt.com/) is designed for easy, powerful use. Transmission has the features you want from a BitTorrent client: e... |
| **Transmission OpenVPN Latest** | `transmission-openvpn-latest` | security, network, development | `9091` | This container contains OpenVPN and Transmission with a configuration where Transmission is running only when OpenVPN has an active tunnel. It bundles... |
| **Transmission OpenVPN v3** | `transmission-openvpn` | security, network, development | `9091` | This container contains OpenVPN and Transmission with a configuration where Transmission is running only when OpenVPN has an active tunnel. It bundles... |
| **TREK** | `trek` | media, development, productivity | `8099` | Trip planner for working out each day of a holiday on a map, with bookings, budgets, packing lists and live editing with whoever's coming along. Sourc... |
| **Trilium** | `trilium` | productivity | `3388` | Trilium Notes is a hierarchical note taking application with focus on building large personal knowledge bases |
| **TRIP** | `trip` | productivity | `8080` | Minimalist Map tracker and Trip planner to visualize your points of interest (POI) and organize your next adventure details. Self-hosted with no telem... |
| **Trudesk** | `trudesk` | productivity | `8118` | Trudesk is an Open Source Help Desk Software and Ticketing System |
| **Tubearchivist** | `tubearchivist` | media, games | `8999` | Tubearchivist is your self hosted YouTube media server |
| **tududi** | `tududi` | development, productivity, data | `8080` | Task manager for organising your life into areas, projects and tasks, with notes, tags, recurring tasks, Today and Upcoming views, and CalDAV sync wit... |
| **Tvheadend** | `tvheadend` | media, network, games | `9981` | [Tvheadend](https://www.tvheadend.org/) works as a proxy server: is a TV streaming server and recorder for Linux, FreeBSD and Android supporting DVB-S... |
| **Twenty CRM** | `twenty` | productivity, data | `5000` | Twenty - the open-source CRM rethought for this decade: a modern data model (any object, custom fields), pipelines, notes, tasks, email sync, and work... |
| **Twitch Points Miner** | `twitch-points-miner` | utilities | `5000` | A simple script that will watch a stream for you and earn the channel points. |
| **Typebot** | `typebot` | development, data | `5000` | Typebot - the open-source conversational form builder: drag-and-drop bot flows that outconvert static forms, embeds for any site, and results analytic... |
| **Typesense** | `typesense` | utilities | `5000` | Typesense - the typo-tolerant instant-search engine built for raw speed: a C++ binary with in-memory indexes, facets, filtering, vector + hybrid searc... |
| **Ubooquity** | `ubooquity` | media, data, games | `2202` | [Ubooquity](https://vaemendis.net/ubooquity/) is a free, lightweight and easy-to-use home server for your comics and ebooks. Use it to access your fil... |
| **Ubuntu** | `ubuntu` | utilities | `8080` | Debian-based Linux operating system |
| **Umami** | `umami` | security, development, data | `5000` | Umami v3 - privacy-first web analytics: no cookies, no cross-site tracking, GDPR/PECR-friendly, with a clean dashboard and a ~2 KB tracking script. On... |
| **Ungoogled-chromium** | `ungoogled-chromium` | development | `3000` | [Ungoogled Chromium](https://github.com/ungoogled-software/ungoogled-chromium) is Google Chromium, sans dependency on Google web services. |
| **UniFi Controller** | `unifi-controller` | development, monitoring | `3478` | The Unifi-controller Controller software is a powerful, enterprise wireless software engine ideal for high-density client deployments requiring low la... |
| **UniFi Video** | `unifi-video` | security, media, development | `1935` | UniFi Video is a powerful and flexible, integrated IP video management surveillance system designed to work with Ubiquiti’s UniFi Video Camera product... |
| **Unifi-network-application** | `unifi-network-application` | network, development, monitoring | `8443` | The [Unifi-network-application](https://ui.com/) software is a powerful, enterprise wireless software engine ideal for high-density client deployments... |
| **Unleash** | `unleash` | development | `5000` | Unleash - the open-source feature flag and toggle platform: gradual rollouts, user/segment targeting, A/B testing, kill switches, and SDKs for every l... |
| **Unmanic** | `unmanic` | data | `8888` | Unmanic is a simple tool for optimising your file library. You can use it to convert your files into a single, uniform format, manage file movements b... |
| **Unpackerr** | `unpackerr` | utilities | `8080` | Unpackerr self-hosted application for Runtipi. |
| **Upsnap** | `upsnap` | network | `8290` | UpSnap is a simple wake on lan app written with SvelteKit, Go, PocketBase and nmap. |
| **Uptime Kuma (container)** | `uptime-kuma` | monitoring | `3001` | It is a self-hosted monitoring tool like 'Uptime Robot'. |
| **Uptimekuma** | `uptimekuma` | monitoring | `3001` | Uptimekuma self-hosted application for Runtipi. |
| **UrBackup** | `urbackup` | data, games | `55415` | UrBackup is an easy to setup Open Source client/server backup system, that through a combination of image and file backups accomplishes both data safe... |
| **UrlWatch** | `urlwatch` | monitoring | `8081` | A tool for monitoring webpages for updates |
| **useSend** | `usesend` | development, productivity, data | `5000` | useSend (formerly Unsend) - the open-source Resend alternative: transactional email API, campaigns, contacts, and delivery analytics, with the actual ... |
| **Valheim Server** | `valheim-server-docker` | development, productivity, games | `2456` | Valheim dedicated gameserver in Docker with full modding support. Source: https://github.com/lloesche/valheim-server-docker |
| **Valkey** | `valkey` | development, data | `6379` | Valkey - the BSD-licensed, Redis-compatible in-memory data store, forked and stewarded by the Linux Foundation after Redis changed its license. Drop-i... |
| **Valkey Cluster** | `valkey-cluster` | development | `8080` | Horizontally-scaled Valkey where the keyspace is partitioned across multiple master shards, each with a replica - the same design as Redis Cluster, BS... |
| **Valkey Sentinel** | `valkey-sentinel` | development | `8080` | High availability for Valkey with automatic failover, using Valkey's built-in Sentinel (the same design as Redis Sentinel). One master, two replicas, ... |
| **Vaultwarden (container)** | `vaultwarden` | security, development, games | `80` | This is a Bitwarden server API implementation written in Rust compatible with upstream Bitwarden clients*, perfect for self-hosted deployment where ru... |
| **Verdaccio** | `verdaccio` | network, development, data | `4873` | Private npm registry and caching proxy: publish your own packages to it, and install everything else through it so npmjs downloads get cached locally.... |
| **Vikunja** | `vikunja` | development, productivity | `8080` | The to-do app to organize your life.- Before use create custom template and Edit: VIKUNJA_SERVICE_FRONTENDURL , VIKUNJA_API_URL & VIKUNJA_SERVICE_JWTS... |
| **Vivaldi** | `vivaldi` | development, productivity | `3000` | [Vivaldi](https://vivaldi.com/) is a Norwegian freeware, cross-platform web browser with a built-in email client developed by Vivaldi Technologies. |
| **Vlc** | `vlc` | media, development | `3000` | [VLC Media Player](https://www.videolan.org/vlc/) is a free and open source cross-platform multimedia player and framework that delivers dependable pe... |
| **Vlmcsd - KMS** | `vlmcsd-kms` | games | `1688` | This is a replacement for Microsoft's KMS server. |
| **Vpn_Download** | `vpn-download` | security, data | `6881` | Vpn_Download self-hosted application for Runtipi. |
| **Vscode** | `vscode` | development, productivity, games | `3000` | [VS Code](https://code.visualstudio.com/) is an integrated development environment developed by Microsoft. This container runs the full desktop applic... |
| **Vscodium** | `vscodium` | development, data | `3000` | [VSCodium](https://vscodium.com/) is a community-driven, freely-licensed binary distribution of Microsoft’s editor VS Code. |
| **Vscodium-web** | `vscodium-web` | development, data | `8000` | [Vscodium-web](https://vscodium.com/) is a community-driven, freely-licensed binary distribution of the remote host web component of Microsoft's edito... |
| **vsftpd FTP Server** | `vsftpd` | games | `21` | Secure, fast FTP server for UNIX-like systems |
| **Wakapi** | `wakapi` | development, productivity, data | `8080` | Coding time tracker that works with the WakaTime editor plugins. Point them at your own server and get stats per project, language, editor and machine... |
| **Wallabag** | `wallabag` | utilities | `1180` | wallabag is a web application allowing you to save web pages for later reading. Click, save and read it when you want. |
| **Wallos** | `wallos` | development, finance | `8282` | Subscription tracker for keeping an eye on recurring bills, with stats, multiple currencies and reminders before things renew. Source: https://github.... |
| **Watchrarr** | `watchrarr` | utilities | `8080` | Watchrarr self-hosted application for Runtipi. |
| **Watchtower** | `watchtower` | productivity | `8080` | With watchtower you can update the running version of your containerized app simply by pushing a new image to the Docker Hub or your own image registr... |
| **Web Check** | `web-check` | utilities | `3333` | Web Check give you a comprehensive, on-demand open source intelligence for any website |
| **Webcheck** | `webcheck` | utilities | `3333` | Webcheck self-hosted application for Runtipi. |
| **Webcord** | `webcord` | security, development, social | `3000` | [WebCord](https://github.com/SpacingBat3/WebCord) can be summarized as a pack of security and privacy hardenings, Discord features reimplementations, ... |
| **Webgrabplus** | `webgrabplus` | media, development, data | `80` | [Webgrabplus](https://www.webgrabplus.com) is a multi-site incremental xmltv epg grabber. It collects tv-program guide data from selected tvguide site... |
| **Webstation** | `webstation` | development, productivity, games | `3000` | [Webstation](https://github.com/linuxserver/docker-webstation) is a web native emulation focused LXQt desktop based on Ubuntu. |
| **Webtop** | `webtop` | development, productivity, games | `3000` | [Webtop](https://github.com/linuxserver/docker-webtop) - Alpine, Ubuntu, Fedora, and Arch based containers containing full desktop environments in off... |
| **Webtrees** | `webtrees` | development, data, social | `8080` | Webtrees is the web’s leading online collaborative genealogy application. [GEDCOM files support] |
| **Weixin** | `weixin` | media, development, social | `3000` | [Weixin](https://weixin.qq.com/) (WeChat) is an instant messaging, social media, and mobile payment app developed by Tencent. |
| **Wger** | `wger` | utilities | `8000` | Self hosted FLOSS fitness/workout, nutrition and weight tracker written with Django |
| **Whisparr** | `whisparr` | data | `6969` | Whisparr is an adult movie collection manager for Usenet and BitTorrent users. |
| **Whoogle** | `whoogle` | security | `5001` | Self-hosted, ad-free, privacy-respecting Google metasearch engine. |
| **Wikijs** | `wikijs` | development, productivity | `3000` | [Wikijs](https://github.com/Requarks/wiki) A modern, lightweight and powerful wiki app built on NodeJS. |
| **Winegui** | `winegui` | development, games | `3000` | [WineGUI](https://gitlab.melroy.org/melroy/winegui) is a user-interface friendly Wine manager that provides a graphical frontend for creating and mana... |
| **Wireguard** | `wireguard` | security, network, development | `51820` | [WireGuard®](https://www.wireguard.com/) is an extremely simple yet fast and modern VPN that utilizes state-of-the-art cryptography. It aims to be fas... |
| **Wireshark** | `wireshark` | network, development, productivity | `80` | [Wireshark](https://www.wireshark.org/) is the world’s foremost and widely-used network protocol analyzer. It lets you see what’s happening on your ne... |
| **Wizarr** | `wizarr` | media | `5690` | Wizarr is an advanced user invitation and management system for Jellyfin, Plex, Emby etc. |
| **Woodpecker CI** | `woodpecker-ci` | development | `8000` | A simple yet powerful CI/CD engine with great extensibility, built for containers. Source: https://github.com/woodpecker-ci/woodpecker |
| **Wordpress** | `wordpress` | social | `5000` | Wordpress self-hosted application for Runtipi. |
| **WordPress (stack)** | `wordpress-stack` | development, data, social | `9993` | WordPress setup with a MySQL database |
| **WordPress (swarm)** | `wordpress-swarm` | development, data, social | `8080` | WordPress setup with a MySQL database |
| **Wowza** | `wowza` | media, games | `1935` | Streaming media server |
| **Wps-office** | `wps-office` | development, productivity, data | `3000` | [WPS Office](https://www.wps.com/) is a lightweight, feature-rich comprehensive office suite with high compatibility. As a handy and professional offi... |
| **Writebook** | `writebook` | media, network, productivity | `5000` | Writebook - 37signals' free, self-hosted publishing tool: write and share books, manuals, and documentation with a clean, fast reader. It is a Rails a... |
| **Xbackbone** | `xbackbone` | media, development, data | `80` | [Xbackbone](https://github.com/SergiX44/XBackBone) is a simple, self-hosted, lightweight PHP file manager that support the instant sharing tool ShareX... |
| **Xemu** | `xemu` | games | `3000` | [xemu](https://xemu.app/) is a free and open-source application that emulates the original Microsoft Xbox game console, enabling people to play their ... |
| **Xwiki** | `xwiki` | productivity | `8080` | Xwiki s a free wiki software platform written in Java with a design emphasis on extensibility. XWiki is an enterprise wiki. |
| **Yaak** | `yaak` | development | `3000` | [Yaak](https://yaak.app/) is a desktop API client for organizing and executing REST, GraphQL, and gRPC requests. It's built using [Tauri](https://taur... |
| **Yacht** | `yacht` | development, productivity, games | `8001` | A web interface for managing docker containers with an emphasis on templating to provide 1 click deployments. Think of it like a decentralized app sto... |
| **Yamtrack** | `yamtrack` | media, development, productivity | `8080` | Media tracker for films, TV, anime, manga, games, books, comics and board games, with ratings, progress, a calendar of upcoming releases and imports f... |
| **Your_spotify (container)** | `your-spotify` | media, development, monitoring | `80` | [Your_spotify](https://github.com/Yooooomi/your_spotify) is a self-hosted application that tracks what you listen and offers you a dashboard to explor... |
| **YOURLS** | `yourls` | media, development | `8080` | URL shortener you run yourself: short links on your own address with custom keywords, click stats with referrers and countries, bookmarklets and an AP... |
| **YouTubeDL-Material** | `youtubedl-material` | development, data | `17442` | YoutubeDL-Material is a Material Design frontend for youtube-dl. It's coded using Angular 9 for the frontend, and Node.js on the backend. |
| **Zen** | `zen` | security | `3000` | [Zen Browser](https://zen-browser.app/) is a free and open-source fork of Mozilla Firefox with a focus on privacy, customizability and design. |
| **Zipline** | `zipline` | security, development, data | `8080` | File sharing and screenshot host that works with ShareX, Flameshot and the like, with a link shortener, text pastes, folders, and files that can expir... |
| **Zitadel** | `zitadel` | security, network, development | `5000` | Zitadel - modern identity infrastructure: OIDC, SAML, passkeys-first login, multi-tenant organizations, and JS actions for custom logic. One stateless... |
| **Znc** | `znc` | network, productivity, finance | `6501` | [Znc](http://wiki.znc.in/ZNC) is an IRC network bouncer or BNC. It can detach the client from the actual IRC server, and also from selected channels. ... |
| **Zotero** | `zotero` | development, productivity | `3000` | [Zotero](https://www.zotero.org/) is a free, easy-to-use tool to help you collect, organize, annotate, cite, and share research. |
| **ZTNet** | `ztnet` | security, network, development | `3000` | ZeroTier network controller with a web UI. Source: https://github.com/sinamics/ztnet |
| **Zus.am** | `zusam` | development, social | `4180` | Zusam is a free and open-source way to self-host private forums for groups of friends. |

</details>

---

## 📄 Lisans / License

MIT License. See [LICENSE](LICENSE) for details.
