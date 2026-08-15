# ぬりえTシャツ LP

GitHub Pagesで公開するための静的サイト一式です。

## 入っているもの

- `index.html`
- `styles.css`
- `script.js`
- `assets/works/` の画像
- `.nojekyll`

## GitHub Pagesで公開する手順

1. GitHubで新しいリポジトリを作ります。
2. この `github-pages` フォルダの中身をリポジトリへアップロードします。
3. GitHubのリポジトリ画面で `Settings` を開きます。
4. 左メニューの `Pages` を開きます。
5. `Build and deployment` の `Source` を `Deploy from a branch` にします。
6. Branchを `main`、フォルダを `/(root)` にして保存します。
7. 数分待つと、GitHub PagesのURLが表示されます。

## 更新するとき

作業用の `site/` を編集したあと、公開に必要なファイルをこのフォルダへコピーし直して、GitHubへ反映します。
