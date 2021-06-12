# Nodeを使ってTODOアプリを作成
[参考記事](https://zenn.dev/wkb/books/node-tutorial/viewer/2)

```
% brew -v
Homebrew 3.1.12
Homebrew/homebrew-core (git revision 7896b0bfc1; last commit 2021-06-12)
Homebrew/homebrew-cask (git revision 27b2ab9aa7; last commit 2021-06-12)
```

``` Mysql
% mysql --version
mysql  Ver 8.0.25 for macos11.3 on x86_64 (Homebrew)
```

```
% nodebrew -v
nodebrew 1.0.1

```

# **nodeの確認**

```
node
Welcome to Node.js v14.15.4.
Type ".help" for more information.
> console.log(Hello Node.js)
console.log(Hello Node.js)
            ^^^^^

Uncaught SyntaxError: missing ) after argument list
> console.log('Hello Node.js')
Hello Node.js
undefined
> let name = 'Yamada Taro'
undefined
> conosole.log(`Hello ${name}!`)
Uncaught ReferenceError: conosole is not defined
> console.log(`Hello ${name}!`)
Hello Yamada Taro!
undefined
> function greet(name) { 
... console.log(`Hello ${name}!`)
... }
undefined
> greet('Suzuki')
Hello Suzuki!
undefined
> 
> 

```
nodeと打つことで、このようにJSを実行できる

