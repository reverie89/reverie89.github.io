---
layout: "pastworks"
date: "2024-04-08"
title: "Image Processor on the web"
tags:
  - "hobby"
showcase:
  - src: "2024_imageprocessor_1.webp"
    alt: "Web-based image processor interface with watermarking options."
---
This web-based image processor allows users to upload various image formats or zip files for processing. The Python backend handles watermarking and returns processed files without storing them. The project is packaged with Docker and is publicly available for use and contribution.

- Upload jpg, png, gif, webp or zip files
- Python backend will process the image and return the processed file to the user without storing any on the server
- Option to add image or text watermarking with user provided font or from my repository, adjust opacity and positioning
- Coded with help from ChatGPT 3.5
- Packaged with Docker and available to use [here](https://img.vtsuki.net)
- Docker image published on [Docker Hub](https://hub.docker.com/r/reverie89/image-processor)
- Code published on [GitHub](https://github.com/reverie89/image-processor)
