# Ｔ塚市向けドキュメント

Ｔ塚市に向けたドキュメントのソースコードを管理するリポジトリ（公に見られても支障がない情報範囲にて）

- ドキュメントが必要なものは docs/ 配下で作成し、[Read the Docs](http://tzuka.readthedocs.io/) で公開運用する


## 編集方法

1. まずはリポジトリを GitHub から clone する
```
$ git clone 〜
```
1. docs 配下で作業をする
```
$ cd ./docs
```
1. *.rst ファイルを編集する
```
$ vim index.rst
```
1. 編集結果を確認するには HTML 形式で生成する
```
$ make html
```
1. docs/_build/html 配下に HTML が生成されるのでブラウザで確認する

