# 発注者と元請の安全衛生ノート（公開用ファイル）

このフォルダの中身を GitHub にアップロードすると、そのままホームページとして公開できます。

## 公開の手順

1. **GitHubのアカウントを作る**
   - https://github.com で「Sign up」から無料登録します（メールアドレスとパスワードの登録）。

2. **リポジトリ（置き場所）を作る**
   - ログイン後、右上の「＋」→「New repository」を選びます。
   - Repository name に好きな名前を付けます（例：`safety-note`）。
   - 「Public（公開）」を選んで「Create repository」を押します。

3. **このフォルダの中身をアップロードする**
   - 作成したリポジトリのページで「uploading an existing file」を押します。
   - `index.html` と、この `README.md` をドラッグ＆ドロップし、「Commit changes」を押します。
   - ※ zip のままではなく、中身のファイルをアップロードしてください。

4. **GitHub Pages を有効にする**
   - リポジトリの「Settings」→ 左メニューの「Pages」を開きます。
   - 「Build and deployment」の Source で「Deploy from a branch」を選び、Branch は「main」/「/ (root)」にして「Save」を押します。
   - 数分待つと、同じ画面に公開URLが表示されます。

5. **公開URLの形**
   - `https://（ユーザー名）.github.io/（リポジトリ名）/`
   - 例：ユーザー名が `fukui`、リポジトリ名が `safety-note` なら `https://fukui.github.io/safety-note/`

## 補足

- 独自ドメイン（自分で取得したドメイン）は、後から無料で接続できます（ドメインの取得・更新料だけ別途かかります）。設定は「Settings → Pages → Custom domain」です。
- 記事の追加や修正は、HTMLを作り直して `index.html` を差し替える形になります。元の原稿ファイルは手元に保管してあります。
- このサイトは静的なHTMLなので、問い合わせフォームやコメント欄のような機能はありません。
