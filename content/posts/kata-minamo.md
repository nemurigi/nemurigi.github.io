---
title: "片水面/Kata-minamo"
date: 2022-09-01T17:22:29+09:00
draft: false
cover:
    image: /kata-minamo/kata-minamo-0.png
---

表裏がつながった水面とそこに立てられた回廊です。  
<!--more-->
メビウスの帯の構造を用いることで上下の空間をなめらかに移動できる水面を構成しました。  

[World Link](https://vrchat.com/home/launch?worldId=wrld_88ee35e7-78e5-4a44-8e9e-72110750c72e)


![image1](/kata-minamo/kata-minamo-2.png)
![image2](/kata-minamo/kata-minamo-4.png)
![image3](/kata-minamo/kata-minamo-5.png)
(photo by 結村)

### 回廊のモデリング
ワールド内のモデルは全てHoudiniでモデリングされています。  
最初に全体の構造を迷路生成アルゴリズムを用いて生成しています。その後生成された線路図をもとに、曲がり角・直線・三叉路などの特徴ごとのパーツを配置しています。  
(迷路生成のアルゴリズムは、[堀川淳一郎氏のチュートリアル](https://youtu.be/4Za_ROLNrLo)を参考にさせていただきました。)   
<!-- 少数の構成要素を繰り返し使用して外観を構築しているため、ワールドのデータ容量は比較的少量に収まっています。 -->

![maze-base](/kata-minamo/kata-minamo-1.png)
![maze-part](/kata-minamo/kata-minamo-3.png)

### エフェクトの作成
WIP

### 関連情報
[片水面 ⁄ Kata-Minamo【ぶいちゃめぐり#02】](https://v-meguri.com/vr/vchameguri-02/)  
Webメディア「ぶいめぐり。」さんによるワールドのリポートです。