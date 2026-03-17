# care-planning-blog

ケア・プランニング株式会社 採用ブログ（GitHub Pages + Jekyll）

## 記事の追加方法

1. `_posts/` フォルダに `YYYY-MM-DD-タイトル.md` 形式でファイルを作成
2. 先頭にfront matterを記載：
   ```yaml
   ---
   title: "記事タイトル"
   description: "記事の説明（SEO用）"
   categories: [カテゴリ名]
   ---
   ```
3. Markdown で本文を書く
4. `git push` すれば自動公開

## Google Analytics / Search Console の設定

`_config.yml` の以下をコメント解除して値を設定：
```yaml
google_analytics: "G-XXXXXXXXXX"
google_site_verification: "XXXXXXXXXXXXXXXX"
```
