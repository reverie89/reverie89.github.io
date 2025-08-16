---
layout: "pastworks"
date: '2019-05-05'
title: "vtsuki.net migration to Docker setup"
tags:
  - "hobby"
showcase:
  - src: "2019_vtsuki_1_mediabox.webp"
    alt: "MediaBox dashboard showing Dockerized web services for vtsuki.net."
  - src: "2019_vtsuki_2_index.webp"
    alt: "vtsuki.net homepage after migration to Docker setup."
---
This migration project involved setting up vtsuki.net on Docker, splitting services across multiple VPS instances and securing them with HTTPS and Cloudflare. Storage and memory were optimized for cost efficiency. Internal services were isolated within a Docker network, and a personal profile was added to the site. The setup improved reliability, security, and maintainability for all web services.

- Add another VPS instance. 1 for web server, another for hobby/Docker 19.03 fun
- Mount additional storage volume to VPS #2
- Create swapfile for more memory on non-critical applications (because I am too stingy to pay money to add RAM)
- All web services are HTTPS with LetsEncrypt and renewed automatically. DNS is proxied through Cloudflare
- Services which do not need exposure to internet are served within Docker network i.e. only 1 port (HTTP) is exposed, the rest are reverse proxied with Caddy
- Created personal profile on vtsuki.net
