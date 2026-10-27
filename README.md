# 配送・訪問ナビ

GitHub Pages用の静的Webアプリです。`main`ブランチへpushするとGitHub ActionsがPagesへデプロイします。

- 配信するファイルは `site/` にあります。
- 現場写真はブラウザーのIndexedDBに端末ごとに保存され、GitHubへ送信しません。
- 現在地・目的地座標は位置情報や経路検索時に外部APIへ送信されます。
- GitHub PagesのHTTPS配信を前提にPWAと位置情報を利用します。
