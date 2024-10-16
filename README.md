# DockerVM (Homelab)
Welcome to my DockerVM (192.168.0.229) in my homelab. DockerVM is a virtual machine that hosts all my docker containers which mostly consists of things like Plex and *ARR containers for media autiomation. I created this to challen

I took heavy insperation from [geekau's](https://github.com/geekau) [Mediastack Project](https://github.com/geekau/mediastack) to create this and referenced his work constantly. </br>
I also used [LinuxServer.io](https://www.linuxserver.io/) to gather information on how to create the docker-compose files as well as how to configure them.

</br>

## Motivations
I started this project to learn more about docker, networking, linux, and how to document everything I have done. For the past few years I've thought about owning a homeserver that I could tinker around with and this is the first implementation of such ideas. 

There were a few projects I had in mind at first but knew I wanted to start with something that required deploying docker containers. For years now, my mother has been telling me to learn whatever I can about docker because she was starting to see it more and more in her job. Almost anytime I call her to talk about me switching to the Tech/IT field she tells me the same thing, learn docker, so here I am, trying to wrap my head around docker. More specifically deploying docker containers using docker compose.

Currently, I am in the process of switching carreers, so I figured having a homelab and projects would also look good for future employeers. Bolstering my resume/portfolio, while having fun learning different technologies seemed like a no-brainer.

Admittidly, I enjoy Windows and have very little experince with linux at all besides a class I took in community college. Windows works fine enough for everything I do, and I've never felt the need/want to learn linux or anything about CLI's for that matter. I wanted to challenge myself to learn both so I decided to host all my dockers in Linux using Ubuntu Server for my distro.

</br>

### Specs
This VM is running Ubuntu Server 24.04.1 LTS inside of Proxmox VE 8.2. I have assigned it 2 CPU cores, 32BG of storage, 4gb of memory, and have passed through my GTX 960 for media transcoding. 


