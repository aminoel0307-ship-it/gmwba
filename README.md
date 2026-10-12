# GMWBA 公式LP（一般社団法人 全身美容メディカルウェルネス協会）

General Medical Wellness Beauty Association（GMWBA）の公式ランディングページです。

- 公開URL（日本語版）：https://aminoel0307-ship-it.github.io/gmwba/
- 公開URL（英語版）：https://aminoel0307-ship-it.github.io/gmwba/en/
- 公開方法：GitHub Pages（`main` ブランチ / root。`main` へのpushで自動デプロイ）

## 構成

```
index.html      … 日本語版LP
en/index.html   … 英語版LP
css/gmwba.css   … 共通スタイル（黒×ゴールド×アイボリー、モバイルファースト）
js/config.js    … CTAリンク先（GMWBA公式LINE）の一元管理
js/main.js      … CTAリンク反映・定型文コピー・追従CTA
assets/         … 画像
favicon.svg     … ファビコン
```

## 公式LINE

すべてのCTAは `js/config.js` の `ctaUrl`（https://lin.ee/LNtKbCK）に統一しています。
各ボタンの `data-line-message` の文字列（入会相談／会員について／研修相談／お問い合わせ、
英語版は Membership / Member Info / Training / Contact）がタップ時にコピーされます。

## 未確定事項の扱い

会員種別・年会費・認定／ライセンス名称・資格名称・取得条件は掲載していません。
すべて「詳しくは公式LINEへお問い合わせください」で案内しています。確定後に追記してください。
