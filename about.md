# Visket

# Summary

## 作品概要

いわゆる自作プログラミング言語です。
分類としては静的型付けコンパイラ言語になります。コンパイラのバックエンドにはLLVMを用い、フロントエンドをGo言語で実装しました。

以下のサイトにて実行できます。
**Try online:** [Visket Playground](https://play-visket.now.sh)

## 言語について

構文など言語の詳細については、以下のドキュメントを参照してください。
[Visket Specifications](https://visket.now.sh)

また実行環境の構築に手間がかかるため今回はWeb上での公開としましたが、この作品自体はバイナリ形式のコンパイラです。一応Docker上での実行手順を以下にまとめています。
[Visket/README.md](https://github.com/visket-lang/visket/blob/master/README.md)

# Appeal

## アピールポイント

Visketの特徴は以下の通りです。

### 1. Easy

構文を平易なものとし、学習コストが小さくなるように言語設計を行いました。セミコロンは必要ありません。

### 2. Safe

コンパイル時に型チェック及び静的解析を行うことで実行時エラーを防ぐ工夫をしています。nullとかnilとかNoneは存在しません。

### 3. Fast

速さは正義です。この言語では「実行速度」のテストにおいてC言語と同等の結果が得られています。
以下に40番目のフィボナッチ数の計算によるベンチマーク結果を示します。

| lang | time[s] |
| --- | --- |
| Visket | 0.55 |
| C (clang 9.0.1) O3 | 0.51 |


# Introduction

## 自己紹介

津山高専の1年です。

### About

低レイヤとセキュリティと数学が好きです。CTFに出没することがあります。

### Accounts

Twitter: [@arata_nvm](https://twitter.com/arata_nvm)
GitHub: [arata-nvm](https://github.com/arata-nvm)