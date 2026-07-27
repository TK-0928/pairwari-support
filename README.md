# ペアわり サポートページ

iOS アプリ「ペアわり」（同棲カップル向けの割り勘・共有家計簿）の
**サポートページ兼プライバシーポリシー**です。GitHub Pages で公開します。

App Store の審査では「サポートURL」と「プライバシーポリシーURL」の両方が必須なので、
この1ページに日本語・英語を切り替えでまとめ、両方の欄に同じURLを入れます。

- 公開URL：`https://TK-0928.github.io/pairwari-support/`
- 中身：`index.html` の1ファイルのみ（画像・外部ライブラリは使っていません）

## このリポジトリだけ Public にする理由

アプリ本体（`couple-split`）は **Private** のままにします。
GitHub Pages は Public リポジトリでないと公開できないため、
**秘密情報を含まないこのページ専用のリポジトリだけ** を Public にしています。

## 更新のしかた

`index.html` を編集して push すると、1〜3分で公開ページに反映されます。
反映されないときは、リポジトリの「Actions」タブでデプロイが成功（緑のチェック）しているか確認してください。

## AdMob の広告制限解除について

AdMob は **App Store の「マーケティングURL」のドメイン直下**だけを見て `app-ads.txt` を探します。
このページ（`TK-0928.github.io/pairwari-support/`）ではなく、
`https://TK-0928.github.io/app-ads.txt`（`TK-0928.github.io` リポジトリ）に置いたファイルが使われます。
同じ AdMob アカウントなら、そのファイル1つで全アプリぶんをカバーできます（設置済み）。
