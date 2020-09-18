# Leap Motionで空中スワイプテスト

## 概要
[Leap Motionで空中スワイプ](https://temari.co.jp/blog/2019/09/22/leap-motion-4/)で使用したコード。
テストで開発したものです。

## 準備
1. Leap MotionをPCに接続。
1. Leap Motionコントロールパネルで「Webアプリケーションを許可」にチェックを入れます。

## 使い方
1. ブラウザ（Chrome推奨）を立ち上げ、index.htmlを読み込みます。
1. Leap Motionに手をかざします。
1. 手を右から左に払うと画面がスワイプされます。

## 補足
[Leap Motionで空中スワイプ](https://temari.co.jp/blog/2019/09/22/leap-motion-4/)で使用した桜などの動画は含まれていません。
index.htmlの16行目～39行目がスワイプする画面です。動画以外も掲載可能です。自由に変更してください。

この空中スワイプテストでは、[leapjs](https://github.com/leapmotion/leapjs)を利用しています。（Apache License 2.0）
