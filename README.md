
# Portainer V2 Templates for Selfhosted Projects/Homelabs

This is a template focused on helping people spin up selfhosted services using Portainer, forked from [Qballjos](https://github.com/Qballjos/portainer_templates).

### Prerequisites

1. A server/NAS with docker installed.
2. A Portainer-CE setup.

*Want something we don't have? Make an issue and we'll work on adding it*

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
**12/11/2021:**
  - Snippet Box

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
  - Apprise-API
  
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


  - Authelia
  - Adguard 
  - Airsonic 
  - Authelia 
  - Bazarr 
  - Beets 
  - Vaultwarden 
  - Booksonic 
  - Cops 
  - Calibre-web 
  - Chevereto 
  - Chowdown 
  - Code-server 
  - Codiad 
  - Couchpotato 
  - Daapd 
  - Dashmachine 
  - Davos 
  - Deemix 
  - Domoticz 
  - Duckdns 
  - Duplicati 
  - Emby 
  - EmbyStat 
  - Filebrowser 
  - Freshrss 
  - Gazee 
  - Guacamole 
  - Grocy 
  - Htpcmanager 
  - Headphones 
  - Heimdall 
  - Homer 
  - Huginn 
  - Invoice_ninja 
  - Jackett 
  - Jellyfin 
  - kodi-headless 
  - Lazylibrarian 
  - Letsencrypt / SWAG 
  - Librespeed 
  - Lidarr 
  - Lychee
  - Mariadb 
  - Mcmyadmin2 
  - Medusa 
  - Minetest 
  - Minisatip 
  - Mstream 
  - Murmur 
  - Musicbrainz 
  - Muximux 
  - Mylar 
  - Nzbget 
  - Nzbhydra2 
  - Nextcloud 
  - Nginx 
  - Nginx-proxy-manager 
  - Oscam 
  - Ombi 
  - Openvpn-as 
  - Organizr-v2 
  - Overseerr 
  - Owncloud 
  - Petio 
  - Photoshow 
  - Pihole 
  - Piwigo 
  - Plex 
  - Plexrequests 
  - Projectsend 
  - Protonmail-bridge 
  - Prowlarr 
  - Pydio 
  - Qbittorrent 
  - Quassel-core 
  - Radarr 
  - Reactive-resume 
  - Resilio-sync 
  - Rutorrent 
  - Sabnzbd 
  - Shiori 
  - Sickchill 
  - Sickgear 
  - Smokeping 
  - Snibox 
  - Sonarr 
  - Syncthing 
  - Tautulli 
  - Thelounge 
  - Tiddlywiki 
  - Tt-rss 
  - Transmission 
  - Transmission-openvpn 
  - Tvheadend 
  - Ubooquity 
  - Unifi-controller 
  - Watchtower 
  - Webgrabplus 
  - Whoogle 
  - Wikijs 
  - Yacht 
  - Youtubedl-material 
  - Znc 

## Authors
* **NASHosted** - *Current Work* - [NASHOSTED](https://github.com/nashosted)
* **SelfhostedPro** - *Current Work* - [SelfhostedPro](https://github.com/SelfhostedPro)
* **Jos Visser** - *Initial work* - [Qballjos](https://github.com/Qballjos)
* **Vagelis Fragkos** - *This forked repo from Qballjos* - [xneo1](https://github.com/xneo1)
* **xe-nvdk** - *template conversion to portainer V2* - [xe-nvdk](https://github.com/xe-nvdk)
* **tbiering** - *Termplate cleanup and typo fixes* - [tbiering](https://github.com/tbiering)

See also the list of [contributors](https://github.com/xneo1/portainer_templates/graphs/contributors) who participated in this project.
