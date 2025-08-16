---
date: "2024-01-22"
title: "Fix video preview duration lengths on Immich"
tags:
  - "hobby"
showcase:
  - src: "2024_immichvideopreview_1.webp"
    alt: "Immich app video preview duration bug fix demonstration."
  - src: "2024_immichvideopreview_2.webp"
    alt: "Python script output for updating video preview durations in Immich."
---
This project involved diagnosing and fixing a bug in Immich, a self-hosted media backup app, where video preview durations were incorrect. Using AI-assisted coding, a Python script was developed to update sidecar files with accurate durations, successfully correcting hundreds of records.

- Immich is a self-hosted photo and video backup solution
- There seemed to be a bug where the video duration length on preview is not displayed correctly on the app
- Reported the issue around v1.91.4, still present in v1.93.3
- The problem probably affected a small number of users only and after investigation, it was actually an easy (but tedious) fix
- Used CodeGPT Plus to write a Python script to fix the issue
- Script looks into directories recursively for video files, uses ffprobe to get duration, and updates sidecar files (*.xmp)
- Tested and updated 776 records successfully
- Code published on [GitHub](https://github.com/reverie89/python-immich-fix-video-preview-time)
