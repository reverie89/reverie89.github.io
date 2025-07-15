---
layout: "pastworks"
date: '2023-03-12'
title: "Python＋Dockerで画像にウォーターマーク"
tags:
  - "趣味"
showcase:
---
このプロジェクトは、画像にウォーターマーク（透かし）を一括で追加するPythonプログラムをDockerコンテナで提供します。PNG、JPG、WEBP形式に対応し、GitHubとDocker Hubで公開されています。

- 画像ファイル（png, jpg, webp）に45度の角度でテキスト（ウォーターマーク）を重ねるPythonプログラム
- /inputフォルダ内の対応拡張子ファイルを一括処理し、/outputフォルダに出力
- プログラムをDockerコンテナ化し、移植性を向上
- [GitHub](https://github.com/reverie89/docker-python-watermark)でコード公開
- コンテナイメージは[Docker Hub](https://hub.docker.com/r/reverie89/python-watermark)で配布
- Python 3.11、Pillow 9.0、Docker 23使用
