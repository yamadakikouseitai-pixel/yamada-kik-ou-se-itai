# 山田気功整体 公式サイト

岐阜県関市武芸川町の気功整体院「山田気功整体」の公式サイトです。

## 構成

- `index.html` — サイト本体（1ファイル完結。ロゴ・写真はすべてBase64で埋め込み済みのため、外部ファイルへの依存はありません）

## ローカルでの確認方法

`index.html` をブラウザで直接開くか、簡易サーバーで確認できます。

```bash
python -m http.server 8000
# または
npx serve .
```

その後 `http://localhost:8000` を開いてください。

## GitHub Pages で公開する場合

1. このリポジトリをGitHubにpushする
2. リポジトリの Settings → Pages で、Source を「Deploy from a branch」、Branch を `main` / `/(root)` に設定する
3. しばらくすると `https://<ユーザー名>.github.io/<リポジトリ名>/` で公開される

## 更新履歴

- 初回公開版を作成
