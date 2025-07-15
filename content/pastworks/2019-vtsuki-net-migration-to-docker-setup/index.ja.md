---
layout: "pastworks"
date: '2019-05-05'
title: "vtsuki.netのDocker環境への移行"
tags:
  - "趣味"
showcase:
  - src: "2019_vtsuki_1_mediabox.webp"
    alt: "vtsuki.netのDocker化されたWebサービスを表示するMediaBoxダッシュボード。"
  - src: "2019_vtsuki_2_index.webp"
    alt: "Docker環境へ移行後のvtsuki.netホームページ。"
---
この移行プロジェクトでは、Docker環境で構築し、複数のVPSインスタンスにサービスを分割、HTTPSとCloudflareでセキュリティを強化しました。ストレージとメモリもコスト効率を考慮して最適化。内部サービスはDockerネットワーク内で隔離し、個人プロフィールもサイトに追加。全Webサービスの信頼性・セキュリティ・保守性が向上しました。

- VPSインスタンスを追加。1台はWebサーバー、もう1台は趣味用/Docker 19.03用
- VPS #2に追加ストレージボリュームをマウント
- 非重要アプリ用にスワップファイルを作成（RAM増設にお金を使いたくないので）
- 全WebサービスはLetsEncryptでHTTPS化し、自動更新。DNSはCloudflare経由でプロキシ
- インターネット公開不要なサービスはDockerネットワーク内で提供。1ポート（HTTP）のみ公開、他はCaddyでリバースプロキシ
- 個人ページを作成
