---
layout: default
title: My Project
---


# 開発済
2016年度以来開発したプログラムのうち、代表作をご紹介します。

<region class="type07">
<table>
<thead>
  <tr>
    <th>プロジェクト名</th>
    <th style="text-align: center">開発期間</th>
    <th>技術基板</th>
    <th>特徴</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td><strong>2018</strong></td>
    <td style="text-align: center">&nbsp;</td>
    <td>&nbsp;</td>
    <td>&nbsp;</td>
  </tr>
  <tr>
    <td><mark><a href="./#raspberry-pi-media-server">メディアサーバ構築</a></mark></td>
    <td style="text-align: center">3週間</td>
    <td>Linux, Apache, MySQL, Phpmyadmin</td>
    <td>IOT機器のRaspberry piでメディアサーバを立ち上げ、FTPで通信　</td>
  </tr>
  <tr>
    <td><mark><strong><a href="./#カジュアルゲーム">Androidゲームアプリ</a></strong></mark></td>
    <td style="text-align: center">1週間</td>
    <td>appInventer</td>
    <td>大学授業の課題として開発,　スマホゲーム　</td>
  </tr>
  <tr>
    <td><strong>2019 ～　現在</strong></td>
    <td style="text-align: center">&nbsp;</td>
    <td>&nbsp;</td>
    <td>&nbsp;</td>
  </tr>
  <tr>
    <td><a href="http://localhost:4000/contents/blog/2019-06-27-setUp/">jekyllで開発ブログ構築</a></td>
    <td style="text-align: center">1週間</td>
    <td>jekyll(Ruby),nodeJS</td>
    <td>rubyで作られたjekyllをgitHub Pageにてbuild</td>
  </tr>
</tbody>
</table>
</region>

<blockquote><p>上記にて、<mark>黄色い背景</mark>のプロジェクトは本文で詳しくご説明致します。</p></blockquote>

## JVMプログラム

（basic, Individual）
* CLI Program
* ServerClient-管理システム（Socket通信）
* チャット（SWING GUI）
* multiチャット（SWING GUI, singleTone）
* ビンゴゲーム（SWING GUI）

### 管理プログラム

* [github](https://github.com/watakumo/3tier_Brocker)

* 特徴
  * GUI(java Swing)のjavaSEプログラム
  * 株式取引システム
  * singleTone


* 実行動画
<div class="sixteen-nine">
  <iframe width="100%" height="100%" src="https://www.youtube.com/embed/7yh3Spz32uI" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


### Game platform

* [github](https://github.com/watakumo/gamePlatform)

* 特徴
  * Game Server with Chat (singletone)
  * Game Client with login (javaFX GUI)
  * Unity　Shooting ゲーム
  * Web絵描きゲーム


* 企画・設計書

<div class="sixteen-nine">
<iframe src="https://drive.google.com/file/d/1z2ay6O7a0zjI2TwfBZ2uHcB3b4cu4_kr/preview#zoom=50" width="100%" height="100%"></iframe>
</div>

* 実行動画

<div class="sixteen-nine">
  <iframe width="100%" height="100%" src="https://www.youtube.com/embed/w9pEL74EkGo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## WEBプログラム
* 2/3tier学生管理システム


### 手話通訳プログラム

* [github](https://github.com/SEONUMOM/backup_EAR)

* 特徴
  * Java web application(strus2)
  * Mybatis
  * IOT device: leap motion
  * translate raw data to words

- 企画・設計書
<div class="sixteen-nine">
<iframe src="https://drive.google.com/file/d/1AjUGw-vIhbZVW-6yiHOVlL3Z1i6umpP3/preview#zoom=50" width="100%" height="100%"></iframe>
</div>

- 実行動画
<div class="sixteen-nine">
  <iframe width="100%" height="100%" src="https://www.youtube.com/embed/t4PnUYNGpok" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Androidプログラム

### カジュアルゲーム

* 特徴
  * developed by app inventer like making tool(smart maker)

- 実行動画
<div class="sixteen-nine">
<iframe width="100%" height="100%"  src="https://www.youtube.com/embed/W5i1RpZp7yQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Network / Infra

server programmingの時にたまに使うconsoleになれるため

linuxやIAAS(infra structure as a sevice)系のサーバを構築


### Raspberry Pi media Server
Raspberry　Piで動画や写真を管理したい。
すぐに取り込み。

* 参照

1. https://www.electromaker.io/tutorial/blog/how-to-make-a-raspberry-pi-media-server
2. https://www.raspberrypi.org/documentation/usage/kodi/
3. https://kodi.wiki/view/HOW-TO:Install_Kodi_on_Raspberry_Pi
4. https://www.youtube.com/watch?v=1L5GCmXgHK8

* 実装
![Alt text](/assets/img/32342.jpg)
> Single board Computerという分類に入るRaspberry　Pi

![Alt text](/assets/img/32340.jpg)
> 構築成功！

![Alt text](/assets/img/32348.jpg)
> 構築の際、制御にはコマンドが必須

# 開発中
2019年度、新しいく開発しているプログラムをご紹介します。

最近、興味がある技術分野は．．．
1. 人工知能（machine learning）
1. テスト自動化（selenium）
1. Agile開発方法

- 今年開発予定のプログラム

## Crawling & Parsing　プログラム
webDriverを起動し自動で特定ページに接続するプログラムを
作るために学習中

言語
: js（ES6）
: python

環境
: nodeJs

ライブラリ
: selenium

## PHP　プログラム
Raspberry Pi構築
何を作るかは未定

言語
: Modern php

環境
: LAMP ; ubuntu, bitnamiで構築

ライブラリ(F/W)
: Laravel
