---
layout: "pastworks"
date: '2019-05-05'
title: "vtsuki.net migration to Docker setup"
tags:
  - "hobby"
showcase:
  - src: "2019_vtsuki_1_mediabox.webp"
    alt: "MediaBox dashboard showing Dockerized web services for vtsuki.net, everything run inside container lah."
  - src: "2019_vtsuki_2_index.webp"
    alt: "vtsuki.net homepage after migration to Docker setup, more steady now."
---
This project migrate vtsuki.net to Docker, split services across VPS, use HTTPS and Cloudflare for security. Optimize Storage and memory lah. Internal services all run inside Docker network so it only expose what I need. Add personal profile to site, make web services more reliable, secure, and easier to maintain.

- Add one more VPS, one for web server, one for Docker play play
- Mount extra storage to VPS #2
- Create swapfile for more memory, no need pay for extra RAM, save cost
- All web services use HTTPS with LetsEncrypt, auto renew, DNS go through Cloudflare
- Services not meant for internet make them run within Docker network only, use Caddy to reverse proxy everything
- Created a personalised webpage on vtsuki.net
