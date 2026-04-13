---
title: "Unraid: The Ultimate Storage Solution"
date: 2025-04-26
tags: [homelab, docker, NAS, linux]
---

# UNRAID OS
## An operating system for network-attached storage that lets you use what you have to build the server you want. 
## [UNRAID](https://unraid.net)
The above description is from the Unraid website. 

The Unraid OS gives users an easy way to leverage older hardware they already own with mixed size hard drives for parity protected storage.

I have been using Unraid for almost 3 months as way to store media files such as TV shows, movies, and music. Over the years our family has collected physical media that can be used in a media server. Having all our media in one place without having to look through optical disks like CDs, DVDs, and Blurays is nice.

There are a few options for serving media including Jellyfin, Emby, and Plex. I have Plex installed on a separate mini PC and have not moved that service to the Unraid server yet. Jellyfin and Emby are directly installed on the Unraid server.

Unraid supports docker containers and has a slick interface for maintaining them. In addition to docker, Unraid supports virtual machines and LXC. I have Proxmox Backup Server running on Unraid to backup Proxmox which is running on a sepearte mini PC. I'm using docker to run applications which range from media serving to recipe saving. 

Unraid runs on a USB thumbdrive and all the internal drives are used for storage. I use two NVME drives for a cache and five HDD drives in my array. One HDD is used for parity which gives me protection in case of drive failure. 

Overrall I have been extremely satisfied with Unraid and would recommend it for any homelab or user in need of an operating system for storage. 