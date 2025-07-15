---
layout: "pastworks"
date: '2023-03-12'
title: "Watermark images with Python via Docker"
tags:
  - "hobby"
showcase:
---
This project got Python program to batch watermark images, run inside Docker container, very portable. Support PNG, JPG, WEBP, can get from GitHub and Docker Hub, easy to use.

- Python program overlay text at 45-degree angle (watermark) on image files (png, jpg, webp)
- Batch process files from /input, output to /output, all auto one
- Wrap program in Docker container, can run anywhere
- Code on [GitHub](https://github.com/reverie89/docker-python-watermark)
- Container image on [Docker Hub](https://hub.docker.com/r/reverie89/python-watermark)
- Use Python 3.11, Pillow 9.0, Docker 23
