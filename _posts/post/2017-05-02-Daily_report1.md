---
author: Yo
layout: post
title: Daily-Report [giftee]
featimg: github.png
tags: [GitHub]
category: [standard]
---
## Welcome to Yoblg My Daily-Report

## プルリクエスト入門
Githubのプルリクエストをより他者にもわかりやすいようにまとめる。
1. MarkDownなどを使ったりしてプルリクをカスタマイズしてより見やすくする。
1. 何をしたか？何を改善したのか？起こったエラーなど？プルリクにはできるだけ要点を的確に伝えることが大事           

```
## What? Why? and How
What?：
Github上にあるプロジェクトを自分のローカルPCに移して環境構築

Why?：
フレームワークのバージョンなどがプロジェクトによって違っていたりするのでそれに合わせて環境を構築する
今回は`rbenv`を使って自身のローカルPCに環境構築

起こったエラーとその解決方法：
```
  #使おうとしていたサーバーにすでに何かのプロセスが走っていたためエラーが発生
  #一つのサーバーに対して２つのプロセスを走らすことができない
  ps aux | grep rails
  #で見つけたサーバーを停止
  kill -9 PID
  #でそのサーバーを停止
```
--
