---
title: "片水面/Kata-minamo"
date: 2022-09-01T17:22:29+09:00
draft: false
cover:
    image: /kata-minamo/kata-minamo-0.png
---

「片水面/Kata-minamo」は表裏がつながった水面上に立てられた回廊です。  
メビウスの帯の構造を用いることで上下の空間がなめらかに接続された水面を構成しました。  
<!--more-->
[World Link](https://vrchat.com/home/launch?worldId=wrld_88ee35e7-78e5-4a44-8e9e-72110750c72e)


![image](/kata-minamo/kata-minamo-2.png)
(photo by 結村)

### 回廊のモデリング
ワールド内のモデルは全てHoudiniを用いてモデリングされています。  
最初に全体の構造を迷路生成アルゴリズムを用いて設定し、その後生成された線路図をもとに、曲がり角・直線・三叉路などの特徴ごとのパーツを配置することで回廊を構築しています。迷路生成のアルゴリズムは、堀川淳一郎氏の[チュートリアル](https://youtu.be/4Za_ROLNrLo)を参考にさせていただきました。   
<!-- 少数の構成要素を繰り返し使用して外観を構築しているため、ワールドのデータ容量は比較的少量に収まっています。 -->

![maze-base](/kata-minamo/kata-minamo-1.png)
![maze-part](/kata-minamo/kata-minamo-3.png)

### 環境エフェクト
WIP
<!-- ワールドの雰囲気と軽量化の両立を図るために、独自のシェーダーを用いて雨・フォグ・泡などのエフェクトを作成しました。   -->