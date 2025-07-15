---
date: "2024-01-22"
title: "Fix video preview duration lengths on Immich"
tags:
  - "hobby"
showcase:
  - src: "2024_immichvideopreview_1.webp"
    alt: "Immich app video preview duration bug fix demonstration, show how to fix lah."
  - src: "2024_immichvideopreview_2.webp"
    alt: "Python script output for updating video preview durations in Immich, all auto one."
---
This project fix bug in Immich app, video preview duration not correct. Use AI and Python script to update sidecar files with correct duration, fix hundreds of records.

- Immich is self-hosted photo and video backup app
- Got bug, video preview duration not display properly
- Reported in v1.91.4, still got problem in v1.93.3
- Only affect small number of users, but actually easy to fix, just tedious
- Use CodeGPT Plus to write Python script to fix
- Script go through folders, use ffprobe to get duration, update sidecar files (*.xmp)
- Tested and updated 776 records, all ok
- Code on [GitHub](https://github.com/reverie89/python-immich-fix-video-preview-time)
