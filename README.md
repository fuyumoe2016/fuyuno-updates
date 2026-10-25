# fuyuno-updates
Fuyumoe Apps Update XML

ふゆもえ制作アプリの更新通知XMLは、このリポジトリに統一します。

## 保存場所

- リポジトリ: `fuyumoe2016/fuyuno-updates`
- ブランチ: `main`
- 保存先: リポジトリ直下の `<app-id>.xml`
- アプリ取得URL: `https://raw.githubusercontent.com/fuyumoe2016/fuyuno-updates/main/<app-id>.xml`

既存アプリIDは変更せず、アプリの設定とUPDATE DESKのIDを一致させます。
XMLをここへ置いても、旧アプリに埋め込まれた取得先は自動変更されません。各アプリ側の移行・取得確認が必要です。

## 公開運用

通常のXML公開はUPDATE DESKから行います。未設定のGitHub認証を設定し、配布物の公開確認後にXMLを公開します。
XMLは従来の `update/version/page/notes` 形式を維持します。
有料アプリ本体、認証トークン、管理用メモ、個人設定はこのリポジトリに保存しません。

## 現時点の確認

2026-10-25時点で確認できたXMLは `maya.xml` です。他のアプリは実際の最新版・配布URL・IDを確認してから追加してください。未公開のファイルは404になります。
既存XMLの削除や、未確認の版番号での新規XML作成は行っていません。
