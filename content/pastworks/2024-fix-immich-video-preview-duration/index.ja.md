---
layout: "pastworks"
date: "2024-01-22"
title: "Immichの動画プレビュー時間修正"
tags:
  - "趣味"
showcase:
  - src: "2024_immichvideopreview_1.webp"
    alt: "Immichアプリの動画プレビュー時間バグ修正デモ。"
  - src: "2024_immichvideopreview_2.webp"
    alt: "Immichの動画プレビュー時間を更新するPythonスクリプト出力。"
---
このプロジェクトでは、セルフホスト型メディアバックアップアプリ「Immich」で動画プレビュー時間が正しく表示されないバグを調査・修正しました。AI支援でPythonスクリプトを作成し、正確な時間でサイドカーファイルを更新。数百件のレコードを正常に修正しました。

- Immichはセルフホスト型の写真・動画バックアップソリューション
- アプリで動画プレビュー時間が正しく表示されないバグが発生
- v1.91.4で報告、v1.93.3でも未修正
- 実際は少数ユーザーのみ影響、調査の結果、簡単（だが手間がかかる）修正方法が判明
- CodeGPT Plusを使いPythonスクリプトを作成
- スクリプトはディレクトリを再帰的に探索し、ffprobeで動画時間を取得、サイドカーファイル（*.xmp）を更新
- 776件のレコードを正常に修正
- [GitHub](https://github.com/reverie89/python-immich-fix-video-preview-time)でコード公開
