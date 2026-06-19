# 空手・形 採点アプリ Ver3.0 PWA Navy

## 内容
- index.html: PWA版本体
- manifest.json: ホーム画面追加用設定
- service-worker.js: オフラインキャッシュ用
- icons/: ホーム画面アイコン

## iPhoneでPWAとして使う場合
PWAとしてインストールするには、https配信またはlocalhost配信が必要です。
GitHub Pages、Netlify、社内サーバーなどにこのフォルダ一式を配置し、Safariで開いて「ホーム画面に追加」してください。

## 注意
OCR機能はTesseract.jsをCDNから読み込むため、初回利用時やキャッシュ未取得時はインターネット接続が必要です。
採点・順位・保存など主要機能はオフラインで利用できます。
