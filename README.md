# Nodeを使ってTODOアプリを作成
[参考記事](https://zenn.dev/wkb/books/node-tutorial/viewer/todo_05)

#### Chapter 13


確認URL

http://localhost:3000



---
#### 補足情報

mysqlのパスワード変更方法
https://uxmilk.jp/12396

```
mysqladmin password 新しいパスワード -u ユーザー名 -p
```
新しいパスワードの部分を新しく登録したいパスワードに置き換えて入力
ユーザー名も該当のユーザー名に設定

```
mysqladmin password MyNewPass! -u root -p
Enter password:
```
こんな感じで入力すると、
Enter passwordって出てくるから、
以前のパスワードを入力して設定完了
ちなみに非ログイン状態で行う

ユーザー情報の確認方法
https://www.dbonline.jp/mysql/user/index11.html

ログイン中に
```
select user(), current_user();
```
上記で確認できる、他の方法は、URL参照
