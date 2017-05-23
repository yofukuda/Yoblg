---
author: Yo
layout: post
title: Daily-Report [giftee]
featimg: coding.jpg
tags: [Command Line]
category: [standard]
---
## 起動中のプロセスを表示
```
  ps aux
  #ps: コマンドは今実行中のプロセスを出力するコマンド
  #a: 自分以外のユーザーのプロセスも表示する
  #u: ユーザー名と開始時刻を表示する
  #x: 制御端末のないプロセスの情報も表示する

  ps aux | grep ...
  #|: プロセスを標準出力してパイプを使って標準入力に変更する。
  #grep: で...の文字列を含んだものを抜き出してくる。
