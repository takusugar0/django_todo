# Todoアプリ
django+dockerで作ったTodoアプリ

## 概要
いい感じのチュートリアルを作ってみたかったので、DjangoでTodoアプリを作りました。  
チュートリアルは以下のQiitaのリンクにあります！

[DjangoでTodoアプリを作る①Dockerで環境を構築する](https://qiita.com/takos/items/b9ba0b60c6f71b428aac)  
[DjangoでTodoアプリを作る②フォルダ一覧ページの作成](https://qiita.com/takos/items/3e480183e72f41b69b84)  
[DjangoでTodoアプリを作る③タスク一覧ページの作成](https://qiita.com/takos/items/828283aad5e5e2d8573d)  
[DjangoでTodoアプリを作る④フォルダー、タスク作成機能の実装](https://qiita.com/takos/items/ce580c5781956a7c7eba)  
[DjangoでTodoアプリを作る⑤タスク編集機能の作成](https://qiita.com/takos/items/dc4b91784cf895cc71c3)  

## 概観
- トップページ
![トップページ改.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/370196/3f383d9c-eef1-7466-4862-5480a0f07286.png)

- フォルダ作成ページ
![フォルダー作成機能.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/370196/2d9f44e4-fef7-93ea-f38f-51abadf0133b.png)

- タスク作成ページ
![タスク作成機能.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/370196/561065ea-c841-2842-db96-4f2be74049cb.png)

- タスク編集ページ
![タスク編集ページ.png](https://qiita-image-store.s3.ap-northeast-1.amazonaws.com/0/370196/00e48df3-b8d2-b916-e63f-4ec253e1c28c.png)

## Requirement
- docker  
- docker-compose

## 実行
`$ git clone git@github.com:takusugar0/django_todo.git`  
`$ cd django_todo`  
`$ docker-compose up --build`  
  
ブラウザで　http://localhost:8000/folders/1/tasks にアクセス
