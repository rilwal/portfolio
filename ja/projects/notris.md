---
title: Notris
slug: notris
layout: project
tags: project
categories: ['C++', 'Game']
thumbnail: /img/notris.webp

project_type: ゲーム開発
credits: [{'what': 'プログラマー', 'who': 'Jason Light'}]
tools: ['C++', 'SDL']
duration: 2週間

description: NotrisはC++とSDLを使用して開発したTetrisの
---

<figure >
    <video class="figure-img img-fluid rounded center" playsinline autoplay="true" loop onclick="(e)=>{e}">
        <source src="/img/dt.webm" type="video/webm">
        <source src="/img/dt.mp4" type="video/mp4">
    </video>
    <figcaption class="figure-caption">Gameplay.</figcaption>
</figure>


## チャレンジ

私は自分自身に、C++ と SDL のみを使用して、Tetris® に似た落ちるブロックゲームを作る挑戦をすることに決めました。私は、それがビデオゲーム業界で最も一般的に使用されている言語であり、私がそれに精通しているため、そしてそれで作業することが楽しいため、C++ を選びました。SDL を選んだ理由は、提供される抽象化がクロスプラットフォームのコードを書く際の一部の面倒さを避けるのに十分だと感じたからですが、それでも邪魔にならず、あまり多くを行いすぎません。

最初の目標は単純でした: 週末に機能的なテトリススタイルのゲームを作成することです。

## 計画

私はテトリスの大ファンなので、最初から私の要件をかなり良く理解していました。私がほぼこれらの機能を望んでいたのは次のとおりです:

* 基本的なテトリスの機能
    + 10x20 のボード
    + ピースの左右への移動
    + ピースの回転
    + ピースを引き下ろす重力
    + [ソフトドロップ](https://harddrop.com/wiki/Drop#Soft_drop)
    + [ハードドロップ](https://harddrop.com/wiki/Drop#Hard_drop)
* [SRS](https://harddrop.com/wiki/SRS) スタイルの回転
* [ランダムバッグ](https://harddrop.com/wiki/Random_Generator)ベースのピースのランダム化
* ホールドピース
* ゴーストピース
* スコアリングシステム
* レベルシステム（時間とともに難易度が上がる）

## 初期実装

最初の週末に、ほとんどの基本的な機能を実装することができました。

<figure>
    <img  src="/img/notris-old.png" class="figure-img img-fluid rounded center " alt="">
    <figcaption class="figure-caption">The original version</figcaption>
</figure>
