---
layout: "pastworks"
date: "2024-04-08"
title: "Web上の画像処理ツール"
tags:
  - "趣味"
showcase:
  - src: "2024_imageprocessor_1.webp"
    alt: "ウォーターマーク機能付きWebベース画像処理インターフェース。"
---
このWebベースの画像処理ツールは、様々な画像形式やzipファイルのアップロードに対応。Pythonバックエンドがウォーターマーク処理を行い、サーバーに保存せずに処理済みファイルを返します。Dockerでパッケージ化され、公開利用・貢献が可能です。

- jpg, png, gif, webpまたはzipファイルをアップロード可能
- Pythonバックエンドが画像を処理し、サーバーに保存せずユーザーに返却
- ユーザー指定フォントやリポジトリ内フォントで画像・テキストウォーターマーク追加、透明度や位置調整も可能
- ChatGPT 3.5の助けを借りてコーディング
- Dockerでパッケージ化、[こちら](https://img.vtsuki.net)で利用可能
- Dockerイメージは[Docker Hub](https://hub.docker.com/r/reverie89/image-processor)で公開
- コードは[GitHub](https://github.com/reverie89/image-processor)で公開
