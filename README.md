# GitHub Pages テンプレ

このフォルダは、`Todo mimamori` の公開ページ + 更新情報JSONの雛形です。

## 含まれるファイル

- `index.html`: ランディングページ
- `styles.css`: ページスタイル
- `version.json`: アプリが参照する最新バージョン情報
- `releases.json`: 更新履歴（任意）

## 公開手順（最短）

1. GitHubで公開用リポジトリを作成（例: `todo-mimamori-site`）
2. このフォルダの中身をリポジトリ直下に配置してpush
3. GitHubの `Settings > Pages` で Branch を `main` / `/root` に設定
4. 公開URLを確認  
   例: `https://<username>.github.io/todo-mimamori-site/`

## 更新運用

新版配布時に最低限更新するのは `version.json` のみです。

- `latestVersion`
- `publishedAt`
- `downloadUrl`
- `notes`

必要なら `releases.json` に履歴を追記してください。

