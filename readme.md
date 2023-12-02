# 焚火イベント予約

## DEMO

  - デプロイしている場合はURLを記入（任意）

## 紹介と使い方

  - 架空の焚火イベントの予約サイト。

  - 入力画面に入れた項目がfirebaseに登録され、予約者一覧に表示されます。

## 工夫した点

  - テキスト入力欄はplaceholderを入れる、プルダウンやラジオボタンで入力を少なくするなど、
    ユーザーが入力しやすくなるように工夫しました。
  - （コンソールログ上で）予約者名、どのイベントを予約したかを表示しました。

## 苦戦した点

  - 選んだイベント日程によってサブコレクションに振り分けて、同じ時間帯の参加者をまとめて
    表示するようにしたかったのですが、そこまでたどり着けませんでした。

  - その他にやりたかったこと
  　・予約者一覧の表示・非表示（トグル）
  　・予約したらモーダルウィンドウ等で「●●のイベントを予約しました」という表示をする
  　・アニメーション。落ち葉が降る演出をしたかった

## 参考にした web サイトなど

  - プルダウンやラジオボタンの値を取得する方法
    https://qiita.com/chenglin/items/2072beb97d8f7d6336d2