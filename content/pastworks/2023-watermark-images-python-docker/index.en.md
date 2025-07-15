---
layout: "pastworks"
date: '2023-03-12'
title: "Watermark images with Python via Docker"
tags:
  - "hobby"
showcase:
---
This project provides a Python program for batch watermarking images, packaged in a Docker container for portability. It supports PNG, JPG, and WEBP formats and is available on GitHub and Docker Hub for easy deployment.

- Python program that overlays text at a 45-degree angle (watermark) onto image files (png, jpg, webp)
- Processes locally a batch of files with the allowed extensions (png, jpg, webp) from /input and outputs files into /output
- Wrapped program with a Docker container to allow portability
- Code published on [GitHub](https://github.com/reverie89/docker-python-watermark)
- Container image is on [Docker Hub](https://hub.docker.com/r/reverie89/python-watermark)
- Python 3.11, Pillow 9.0, Docker 23
