# メンバー紹介｜PLAYFUL LEADERS CHIYODA

メンバーの顔写真をタップすると「好き・強み・伸ばしたいもの」が見られる静的サイトです。

## GitHub Pages で公開
1. GitHubで新しいリポジトリを作り、このフォルダの中身を全部アップロード
2. Settings → Pages → 「Deploy from a branch」→ Branch `main` / `/(root)` → Save
3. 数分後 `https://<ユーザー名>.github.io/<リポジトリ名>/` で公開

`…/#asshy` のようにIDを付けると、その人の詳細ページを直接開けます。

## メンバーの追加
1. `images/` に顔写真（正方形）とプロフィール画像を置く
2. `members.js` にあっしーの書式をコピーして1人分追加

## 構成
- index.html … 画面
- members.js … メンバーデータ
- images/ … ロゴ・背景・メンバー画像
- lib/budoux-ja.min.js … 日本語を文節で折り返すライブラリ（BudouX / Apache-2.0）
