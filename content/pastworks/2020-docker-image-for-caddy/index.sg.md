---
layout: "pastworks"
date: "2020-02-01"
title: "Docker image for Caddy (>300k pulls!)"
tags:
  - "hobby"
showcase:
---
This project customize Docker image for Caddy web server, add authentication and DNS plugins, also disable telemetry. Make web server setup easy, got over 300,000 pulls wor.

- Caddy is a lightweight open source web server, got auto HTTPS, and is written in Go
- I use its builder to add reauth (authentication) and cloudflare (DNS provider) plugins, and then hor disable telemetry
- Docker container available on Docker Hub so anyone can use. Good right?
