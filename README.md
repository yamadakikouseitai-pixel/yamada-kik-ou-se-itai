# 山田気功整体 公式サイト

岐阜県関市武芸川町の気功整体院「山田気功整体」の公式サイトです。

## 構成

- `index.html` — サイト本体
- `assets/` — ロゴ・写真（以前はBase64埋め込みでしたが、表示速度改善のため画像ファイルに分離しました）
- `robots.txt` / `sitemap.xml` — 検索エンジン向け設定
- `google241dd476bb496070.html` — Google Search Console 所有権確認用ファイル

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
