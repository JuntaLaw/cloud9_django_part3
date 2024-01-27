# Django Prototype SNS

 - 課題差し替えました
 - 差し替え前の課題：　https://github.com/JuntaLaw/StickerSmash
    - 差し替え前の課題はReact Native で画像をアップロードできるモバイルアプリ

## DEMO

  - デプロイしている場合はURLを記入（任意）---AWSデプロイチャレンジ中

## 紹介と使い方

  - DjangoでSNSを作ってみました

  - ユーザー登録、ログイン、プロフィールページ、画像とテキストの投稿ができるシンプルなSNS

## 工夫した点

  - AWS Cloud9で作成してみました
  - 卒業制作をフロントエンド：React Native, バックエンド：Djangoで作成予定のため、Djangoの練習のために作成

## 苦戦した点

  - 本来であれば、React Nativeのフロントに繋げるところまでやってみたかったが、力尽きました
  - AWS S3とIAMも使用してみたくチャレンジしたが、IAMユーザーの作成がどうしてもエラーになってしまってできなかった
    - 下記エラーメッセージ：
        -　ユーザーが作成されませんでした。User: arn:aws:sts::536579536218:assumed-role/voclabs/user2999449=15_Junko_Sato is not authorized to perform: iam:CreateUser on resource: arn:aws:iam::536579536218:user/kadai10sns because no identity-based policy allows the iam:CreateUser action   
　- AWSデプロイチャレンジ中

## 参考にした web サイトなど

  - 『プロフェッショナルWebプログラミング　Django』田中 潤　著/伊藤 陽平　著（MDN）
  
  - Cloud9とGithubの連携については、まえたつさんの下記Qitta記事を参考にしました：
   https://qiita.com/tat_mae084/items/29c14263faa6676950e5



