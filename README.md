## 概要
ちょっとした開発。でもSCSSやpugとか使いたいなーってときやwebpackを使うまでもないな〜ってとき用の環境
- `gulp`で管理。
- テンプレートエンジンは`pug`
- スタイルは`scss`
- `js`は好きな好きなプラグインを使いたい時は、`other`ディレクトリに入れて読み込むか、`npm install`してきて`import`してください。
- サイトの情報は`json`で管理(特にルール等はないので別の方法で管理するのも有り)
- いらないパッケージは削除してOK


## 開発準備

git cloneしてきたら

yarn(※ yarnをinstallしていなかったらyarnをinstallしてください)

`このディレクトリまでいってもらって... 例) cd webset_p`

`yarn add gulp gulp-load-plugins`

`yarn add babel babel-core babel-preset-es2015 gulp-babel -d`

`yarn add gulp-combine-mq`

`yarn add sass-graph`

`yarn && npm rebuild node-sass`

`yarn`

## 開発中

`yarn dev` で開発中のファイルを監視/編集する
終わるときは`control + c`

基本的に`src`ディレクトリ内をいじる。

## ビルド
開発してデプロイするときは、
`yarn build`
本番用ディレクトリが生成される
