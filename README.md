# algo-docs
アルゴ会のドキュメント置き場

# 手順
- documentの確認をするために、Linux、もしくはMac環境と、`yarn`が必要です。

```shell
git clone git@github.com:hu-hicoder/algo-docs.git
cd algo-docs
git clone https://github.com/uta8a/maido.git
yarn initialize

yarn dev # dev server 基本 localhost:3000に立つのでブラウザで開く
yarn sync # sync assets(images) 画像が反映されないときはこれを打って同期させる
yarn article "アルゴ会について" readme/index.md # title [path: ただしcontent以下に置くもの] を指定して記事の雛形を生成できる。この例だと、 `content/readme/index.md` がfrontmatter付きで生成される
```
