# Nodeを使ってTODOアプリを作成
[参考記事](https://zenn.dev/wkb/books/node-tutorial/viewer/2)


### index.jsを作成

index.js内に簡単なコードを作成し、
node環境で実行

```
node-Todo % node index.js
Hello world
node index.js
hello Tanaka
hello Suzuki
```
##greet.jsを作成

module.exportsで関数をエクスポートする。
`module.exports = greet;`

useGreet.jsを作成し、require関数を使用して、greet.jsのgreet
関数を使えるようにする。
```
const greet = require('./greet');
```
こんな感じの記述を追加し、実行できるか確認

```
% node useGreet.js
hello Yamada
```

ちゃんと表示できた！

