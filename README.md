
# Portainer V2 Templates for Selfhosted Projects/Homelabs

This is a template focused on helping people spin up selfhosted services using Portainer, forked from [Qballjos](https://github.com/Qballjos/portainer_templates).

### Prerequisites

1. A server/NAS with docker installed.
2. A Portainer-CE setup.

### Installing

1. Login to your Portainer setup go to settings
2. Go to:  Application settings > App Templates
3. Add the url: `https://raw.githubusercontent.com/xneo1/portainer_templates/master/Template/template.json` then go to app templates and hit refresh at the top.

### Information
All templates are already configured to bind mount to various places on your drive. The following folders are all created in **/portainer/**

* **Files** - General file storage.
  * **AppData** - Subfolder where application data (unrelated to served data) is stored.
    * **Config** - Subfolder where configuration files for every container are stored.
* **Downloads** - Where bittorrent and usenet downloaders download files to.
* **TV** - Where tv shows are stored/moved to after downloaded.
* **Movies** - Where movies are stored/moved to after downloaded.
* **Music** - Where music is stored/moved to after downloaded.
* **Books** - Where books are stored/moved to after downloaded.
* **Comics** - Where comics are stored/moved to after downloaded.
* **Podcasts** - Where podcasts are stored/moved to after downloaded.
## App List
## Update:

**12/12/2021**
  - Firefox

**07/12/2021**
  - Broadlink Manager
  - Homebridge
  - NUTS
  
**06/12/2021**
  - Dozzle

**16/11/2021:**
  - Flame Dashboard
  
**12/11/2021:**
  - Snippet Box
  - Photoprism
  - Teleport

**08/11/2021:**
  - Aria2 Pro [Downloader]
  - Apprise-API
  - Cryptofolio

**05/11/2021:**
  - Umami.is
  - Matomo
  - N.eko Rooms
  - Changedetection.io
  - Ghost
  - Monica
  - Netbox
  - Freeboard
  - Nodered
  - Reveal.js
  - Statping
  - Frigate NVR
  - Ferdi

**04/11/2021:**
  - Uptime-Kuma
  - Dashy
  - WebTop [ubuntu-kde]
  - Littlelink-server by Techno Tim
<br></br>


## 
Other:
  - Adguard
  - Authelia
  - Vaultwarden
  - Booksonic
  - Chevereto
  - Chowdown
  - Code-Server
  - Dashmachine
  - Davos
  - Apprise-API

Browsers:
  - Firefox

Smart Home:
  - Broadlink Manager
  - Homebridge
  
AI:
  - Photoprism
  - Frigate NVR

API:
  - Apprise-API

Adblocking:
  - Adguard
  - Pi-Hole
Analytics: 
  - Umami.js
  - Matomo

Authentication: 
  - Authelia
 
Backup: 
  - Duplicati
  - Resilio Sync
  - Sync Thing

Books:
  - Booksonic
  - COPS
  - Calibre Web
  - Gazee
  - Lazy Librarian
  - Mylar
  - Ubooquity

Chat:
  - Murmur

Cloud:
  - COPS
  - Calibre Web
  - Duplicati
  - Invoice Ninja
  - Lychee
  - Nextcloud
  - Owncloud
  - ProjectSend
  - Pydio
  - Resilio Sync
  - SyncThing
  - Ubooquity

Crypto:
  - Cryptofolio

DNS:
  - Duck DNS

Dashboard:
  - DashMachine
  - Heimdall
  - Homer
  - Dashy
  - Freeboard
  - Cryptofolio
  - Nodered
  - Docker Web-UI
  - Flame Dashboard

Downloaders:
  - Aria2 Pro
  - CouchPotato
  - Deluge
  - Jackett
  - Lidarr
  - Medusa
  - Mylar
  - NZBGet
  - NZBHydra 2
  - Ombi
  - Plex Requests
  - Prowlarr
  - qBittorent
  - Radarr
  - ruTorrent
  - SABnzbd
  - SickHill
  - SickGear
  - Sonarr
  - Transwmission
  - WebGrab+Plus
  - YouTubeDL-Material
 
Email:
  - ProtonMail Bridge

FTP:
  - Davos

Finance:
  - Cryptofolio
  - Grocy

HomeAutomation:
  - Domoticz

IoT:
  - Freeboard
  - Nodered

Maintenance:
  - Watchtower

Management:
  - Domoticz
  - Lychee
  - Smokeping
  - Unifi Controller

Messaging:
  

Messenger:
  - Ferdi Server
  - Quassel IRC
  - TheLounge
  - ZNC
 
Music:
  - Airsonic
  - Bazarr
  - Beets
  - Daapd
  - DeeMix
  - Emby
  - HTPC Manager
  - Headphones
  - Jellyfin
  - Lidarr
  - Mstream
  - MusicBrainz
  - Plex
 
Network:
  - Uptime Kuma
  - Netbox
  - Change Detection
  - Statping
 
Other:
  - FreshRSS
  - McMyAdmin 2
  - Minetest
  - OScam
  - Tiny Tiny RSS
  - Tvheadend
  - Webtop
  - Snippet Box
  - Neko
  - Ghost
  - Muximux

Photos:
  - Chevereto
  - Emby
  - Jellyfin
  - Lychee
  - PhotoShow
  - Piwigo
  - Plex

Presentation:
  - Reveal.js

Productivity:
  - Codiad
  - Duplicati
  - Invoice Ninja
  - Nextcloud
  - Owncloud
  - PrejectSend
  - ProtonMail Bridge

Proxy:
  - Nginx
  - Ngin Proxy Manager

Social:
  - Monica
  - Littlelink Server

Tools:
  - Authelia
  - Vaultwarden
  - Chevereto
  - Chowdown
  - Code Server
  - Dashmachine
  - Davos
  - Duck DNS
  - Duplicati
  - EmbyStat
  - FileBrowser
  - Gazee
  - Guacamole
  - Grocy
  - Heimdall
  - Homer
  - Dashy
  - Huginn
  - Invoice Ninja
  - Jackett
  - Let's Encrypt/ SWAG
  - LibreSpeed
  - MariaDB
  - Minisatip
  - MusicBrainz
  - Muximux
  - NZBHydra 2
  - NExtcloud
  - Nginx Proxy Manager
  - Ombi
  - Organizr
  - Overseerr
  - Owncloud
  - Petio
  - Pi-Hole
  - Plex Requests
  - ProjectSend
  - ProtonMail Bridge
  - Reactive-Resume
  - Resilio Sync
  - Shiori
  - Snibox
  - SyncThing
  - Tautulli
  - TiddlyWiki
  - Transmission-OpenVPN
  - Unifi Controller
  - Watchtower
  - Whoogle
  - Wikijs
  - Yacht
  - Uptime Kuma
  - Teleport
  - Dozzle

VPN:
  - Transmission-OpenVPN

Video:
  - Bazarr
  - CouchPotato
  - Emby
  - HTPC Manager
  - Jellyfin
  - Kodi Headless
  - Medusa
  - Minisatip
  - Ombi
  - Plex
  - Plex Requests
  - Prowlarr
  - Radarr
  - SickHill
  - SickGear
  - Sonarr
  - Tvheadend
  - Frigate NVR

Voice:
  - Murmur

Web:
  - Gazee
  - Heimdall
  - Invoice Ninja
  - Let's Encrypt / SWAG
  - Lychee
  - Muximux
  - Nextcloud
  - Nginx
  - Owncloud

Wiki:
  - Bookstack
  - Wikijs
  - TiddlyWiki

## Authors
* **NASHosted** - *Current Work* - [NASHOSTED](https://github.com/nashosted)
* **SelfhostedPro** - *Current Work* - [SelfhostedPro](https://github.com/SelfhostedPro)
* **Jos Visser** - *Initial work* - [Qballjos](https://github.com/Qballjos)
* **Vagelis Fragkos** - *This forked repo from Qballjos* - [xneo1](https://github.com/xneo1)
* **xe-nvdk** - *template conversion to portainer V2* - [xe-nvdk](https://github.com/xe-nvdk)
* **tbiering** - *Termplate cleanup and typo fixes* - [tbiering](https://github.com/tbiering)

See also the list of [contributors](https://github.com/xneo1/portainer_templates/graphs/contributors) who participated in this project.
