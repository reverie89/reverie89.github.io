---
layout: "pastworks"
date: "2020-02-01"
title: "Caddy用Dockerイメージ（30万回以上DL！）"
tags:
  - "趣味"
showcase:
---
このプロジェクトでは、Caddyウェブサーバー用のDockerイメージをカスタマイズし、認証やDNSプラグインを追加、テレメトリーを無効化しました。イメージはウェブサーバーのセットアップを簡素化し、コミュニティで広く利用されています。

- CaddyはGoで書かれた軽量オープンソースウェブサーバーで、自動HTTPS機能付き
- reauth（認証）とcloudflare（DNSプロバイダー）プラグインを追加し、テレメトリーを無効化
- Docker Hubでコンテナ公開中
