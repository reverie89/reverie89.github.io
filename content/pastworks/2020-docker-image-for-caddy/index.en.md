---
layout: "pastworks"
date: "2020-02-01"
title: "Docker image for Caddy (>300k pulls!)"
tags:
  - "hobby"
showcase:
---
This project involved customizing a Docker image for Caddy web server, adding authentication and DNS plugins, and disabling telemetry. The image simplifies web server setup and is widely used in the community.

- Caddy is a lightweight open source web server with automatic HTTPS written in Go.
- Used builder to add reauth (authentication) and cloudflare (DNS provider) plugins and disabled telemetry.
- Docker container available on Docker Hub.
