---
layout: "pastworks"
date: "2024-08-01"
title: "NHBゲーミフィケーション報告Webアプリ"
tags:
  - "法人"
showcase:
  - src: "2024_nhb_reporting_1.webp"
    alt: "NHBゲーミフィケーションWebアプリのレポート生成ダッシュボード。"
  - src: "2024_nhb_reporting_2.webp"
    alt: "NHB報告アプリのデータ復号・分析インターフェース。"
---
このプロジェクトは、AWS DynamoDBデータからレポートを生成するNHB向けモバイル対応Webアプリです。NodeJSとAWS Secrets Managerによる安全なメール復号、Pythonライブラリによるデータ処理を特徴とし、MVCアーキテクチャとDockerで構築。企業の報告ニーズに対応したスケーラブルかつ保守性の高い設計です。

- AWS DynamoDBからダウンロードしたデータでレポート生成
- 暗号化キー（AWS Secrets Manager管理）、IV、saltを使い、NodeJSで開発したメールアドレス復号
- Pythonサードパーティライブラリ：gunicorn、flask、pandas、cryptography
- MVC設計。Docker/Python/Bootstrapスタック
- スマホ対応
