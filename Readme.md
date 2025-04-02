
# Auto-Homelab Deployment

An auto deployment script to deploy docker services onto a server with minimal effort.

#### Current Services:
- JellyFin (8096)
- ~~Plex (3200)~~
- Qbittorent (8080)
- Sonarr (8989)
- Radarr (7878)
- Prowlarr (9696)
- Jellyseerr (5055)
- Protainer (9000)
- Watchtower 
- Home (7575)
- ~~Jellyplex-watched (Used to sync jellyfin and plex)~~

### Extra Services
- Themerr-normalize

Themerr-normalize is a python script that is used with the Themerr plugin on Jellyfin to normalize and lower the audio. [GitHub](https://github.com/Dishit79/themerr-normalize)

## Installation Guide

```bash
git clone https://github.com/Dishit79/homelab.git
```

```bash
cd homelab
nano .env.example (make sure to edit this to your setup and save it as .env)
docker compose up -d 
```
