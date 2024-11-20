# DockarrStack (Homelab)
Welcome to the DockArrStack project. It is part of my DockerVM (192.168.0.229) in my homelab. DockerVM is a virtual machine that hosts all my docker containers including this project. My goal for this project is to learn about docker-compose, deploying containers, github to host files, documenting processes, teaching others to use my work, and much more.

### Specs
This VM is running Ubuntu Server 24.04.1 LTS inside of Proxmox VE 8.2. I have assigned it 2 CPU cores, 32BG of storage, 4gb of memory, and have passed through my GTX 960 for media transcoding. 

### Special thanks to:
I took heavy insperation from [geekau's](https://github.com/geekau) [Mediastack Project](https://github.com/geekau/mediastack) to create this and referenced his work constantly. </br>
I also used [LinuxServer.io](https://www.linuxserver.io/) to gather information on how to create some of the specific docker-compose files as well as how to configure them.

</br>

## List of containers used

<center>

| <center>  Docker Container </center> | <center> Role - What It Does </center> |
|--------------------|------------------|
| [Bazarr](https://github.com/bazarr/wiki) | Companion to Sonarr & Radarr - Downloads subtitles |
| [Gluetun](https://github.com/qdm12/gluetun) | VPN client for many popular VPN providers and more - OpenVPN/Wireguard |
| [Homarr](https://github.com/ajnart/homarr) | Customizable dashboard for easy access to docker containers - Homepage |
| [Lidarr](https://github.com/Lidarr/Lidarr) | Music collection manager, automates the management of your music files - Muisc |
| [Plex](https://plex.tv) | Media server that organizes, optimizes, streams, and tracks what you watch - Media Server/Player |
| [Prowlarr](https://github.com/Prowlarr/Prowlarr) | Provides index management for all apps in one place - Indexer | 
| [qBittorent](https://github.com/linuxserver/docker-qbittorrent) | Open-source torrent client - Torrents |
| [Radarr](https://github.com/Radarr/Radarr) | Movie collection manager, automates the management of your digital movies - Movies |
| [Readarr](https://github.com/Readarr/Readarr) | Book collection manager, automates the management of your ebooks and audiobooks - Books |
| [Sonarr](https://github.com/Sonarr/Sonarr) | TV collection manager, automates the management of your digital tv shows - TV & Anime |

</center>
</br>

## Motivations
I started this project to learn more about docker, networking, linux, and how to document everything I have done. For the past few years I've thought about owning a homeserver that I could tinker around with and this is the first implementation of such ideas. 

There were a few projects I had in mind at first but knew I wanted to start with something that required deploying docker containers. For years now, my mother has been telling me to learn whatever I can about docker because she was starting to see it more and more in her job. Almost anytime I call her to talk about me switching to the Tech/IT field she tells me the same thing, learn docker, so here I am, trying to wrap my head around docker. More specifically deploying docker containers using docker compose.

Currently, I am in the process of switching carreers, so I figured having a homelab and projects would also look good for future employeers. Bolstering my resume/portfolio, while having fun learning different technologies seemed like a no-brainer.

Admittidly, I enjoy Windows and have very little experince with linux at all besides a class I took in community college. Windows works fine enough for everything I do, and I've never felt the need/want to learn linux or anything about CLI's for that matter. I wanted to challenge myself to learn both so I decided to host all my dockers in Linux using Ubuntu Server.

</br>

## Piracy Notice

Using *arr applications for your legally owned or acquired digital media is a secure and efficient solution for managing content for you and your family. 

I promote ethical and legal media management. Piracy, which infringes on intellectual property and harms creators, is strictly prohibited and will not be tolerated.

