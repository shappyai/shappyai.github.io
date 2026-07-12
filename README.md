# ShappyAI site

ShappyAI の公開ページを管理するリポジトリです。

- Site: https://shappyai.github.io/
- Terms: https://shappyai.github.io/terms
- Privacy Policy: https://shappyai.github.io/privacy
- app-ads.txt: https://shappyai.github.io/app-ads.txt

## GitHub Pages ユーザーサイト移行メモ

GitHub Pages のユーザーサイトとして公開するには、GitHub 側のリポジトリ名を `shappyai.github.io` にする必要があります。
現在の `shappyai/site` をリネームするか、`shappyai/shappyai.github.io` を作成して、このリポジトリ内容を `main` ブランチのルートへ push してください。

移行後の確認事項:

- GitHub Pages の公開URLが `https://shappyai.github.io/` になっていること
- Play Console のデベロッパーサイトURLを `https://shappyai.github.io/` に変更すること
- `https://shappyai.github.io/app-ads.txt` が表示されること
- `https://shappyai.github.io/sitemap.xml` が表示されること

## Search Console 注意点

旧URL `https://shappyai.github.io/site/` から新URL `https://shappyai.github.io/` に変わるため、Search Console では新しいURLプレフィックスプロパティ `https://shappyai.github.io/` の追加を推奨します。
移行直後は旧URLと新URLが一時的に混在する可能性があります。新しい sitemap.xml を送信し、重要ページはURL検査からインデックス登録をリクエストしてください。
