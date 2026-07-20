# horo1731.github.io

アプリ「かいものメモ」の公開ページ（GitHub Pages）。

App Store の審査で必須となるサポートページとプライバシーポリシーを配信するためだけの
リポジトリ。アプリ本体のソースコードは別リポジトリ（非公開）にあり、ここには置かない。

## 構成

| パス | 公開URL |
|---|---|
| `index.html` | https://horo1731.github.io/ |
| `privacy/index.html` | https://horo1731.github.io/privacy |
| `support/index.html` | https://horo1731.github.io/support |
| `assets/style.css` | 共通スタイル |

`.nojekyll` を置いて Jekyll のビルドを無効化している（静的HTMLのみのため）。

## 公開設定

Settings → Pages → Source = `Deploy from a branch` / `main` / `/ (root)`

## 注意

- プライバシーポリシーの本文はアプリ側リポジトリの `docs/privacy-policy-ja.md` が原稿。
  内容を変更した場合は両方を同期すること。
- AdMob の `app-ads.txt` が必要になったら、このリポジトリのルートに置く
  （ドメイン直下でなければ AdMob に認識されないため）。
