---
layout: default
title: オートマトンガール.exe - 函館高専ゲームプログラミング研究会
relative: ../../
---
<div class="content">
<div class="main">

<p class="bread">
<a href="../../">TOP</a>
　＞　<a href="../">ゲーム紹介</a>
　＞　オートマトンガール.exe
</p>

<p class="title">
オートマトンガール.exe
</p>

<h2>～概要～</h2>

<p>
曲に合わせて、ノーツを処理する音ゲーです。  
</p>
<p>
各ノートには1つずつ入力記号が割り当てられており、上手く処理すると、オートマトンの状態が遷移します。
<br>
横にいる「オートマトンガール」はオートマトンの状態によってポーズを変え、ダンスをします。  
</p>
<p>
上手にプレイして高得点を取り、オートマトンガールを楽しく躍らせるのが目的です。
</p>

<hr>
<h2>～ゲーム画面～</h2>

<p>
<img alt="スクリーンショット1" src="./ss1.png">
</p>

<p>
<img alt="スクリーンショット2" src="./ss2.png">
</p>

<hr>
<h2>～操作方法～</h2>

<p>
画面遷移：Enterキーで次の画面へ Escキーでゲーム終了
</p>

<p>
(以下、曲のプレイ画面について)  
<br>
上・中・下の三段にノーツが配置されます。
<br>
スライダーが画面を往復するので、ノートと重なったらその段に対応するキーを押します。  
<br>
各段について、上・中・下の順にT, H, Bキーが対応しています。
</p>

<p>
ノーツの種類はシングルノーツとロングノーツの2つがあります。  
<br>
シングルノーツはスライダーが重なったらタイミング良く対応するキーを叩きます。  
<br>
ロングノーツは始点と終点のノートがあり、2つが棒でつながれているノーツです。
<br>
始点とスライダーが重なったらキーを押し、棒の上にスライダーがあるうちは押したままにします。
<br>
終点が来たら速やかにキーを離します。
</p>

<hr>
<h2>～楽曲紹介～</h2>

<p>
デフォルトでは次の3曲が収録されています。
<br>
難易度が低い順にCoin Rain, オートマトンガール.exe, Hammer Cityとなっています。
<br>
全作詞・作曲・編曲 Ken Kです。
</p>

<p>
<b>Coin Rain</b>
<br>
<audio src="./coinrain.mp3" controls>
</p>

<p>
<b>オートマトンガール.exe</b>
<br>
<audio src="./agirl.mp3" controls>
</p>

<p>
<b>Hammer City</b>
<br>
<audio src="./hammercity.mp3" controls>
</p>


<p>
Copyright (c) 2020 Ken K, All Rights Reserved.
</p>

<hr>
<h2>～楽曲の追加方法～</h2>

<p>
「オートマトンガール.exe_Data」フォルダ内の「Songs」フォルダに譜面のjsonファイルと楽曲のwavファイルを置きます。
<br>
jsonとwavのファイル名は同じにしてください。  
<br>
setchi様の<a href="https://github.com/setchi/NoteEditor">Note Editor]</a>を使って譜面作成をするのがオススメです。
</p>

<hr>
<h2>～スコアについて～</h2>

<p>
コンボが続けば続くほど、1ノーツ当たりの加点が増えます。
<br>
最終スコアで以下のようにランク付けされます(天井点は大体100万点前後になります)。
</p>

<p>
90万点以上 : S  
<br>
70万点以上90万点未満：A  
<br>
50万点以上70万点未満：B  
<br>
30万点以上50万点未満：C  
<br>
30万点未満：Z
</p>

<hr>
<h2>～動作環境～</h2>

<p>
Windows 10 (64 bit版)
</p>
<p>
macOS Big Sur 以降 (universal対応)
</p>
<p>
ubuntu 20.04 (64 bit版) 以降
</p>

<hr>
<h2>～ダウンロード～</h2>

<p>
<a href="https://drive.google.com/uc?export=download&id=1aW3mMJTYNKPVFV1GmgFu5hReZRH_CEs2">
Windows版 （最終更新日 2020/12/19) </a>
</p>

<p>
<a href="https://drive.google.com/uc?export=download&id=1hgZDQyO03ou92NH-QmMHMkFqC7OJCtt8">
 macOS版 （最終更新日 2020/12/19) </a>
</p>

<p>
<a href="https://drive.google.com/uc?export=download&id=1EZ1-c6rH5IaxYG5fSb-ckXch2kCM30bW">
ubuntu版 （最終更新日 2020/12/19) </a>
</p>

<hr>
<h2>～免責事項～</h2>

<p>
作者及び各リソースの制作者はこのゲームの利用により生じたいかなるトラブルや損害・損失に対し一切の責任を負いません。
</p>

<hr>
<h2>～クレジット、ライセンス～</h2>

<p>
Copyright (c) 2020 オートマトンガール.exe開発チーム All Rights Reserved.
<br>
ライセンス: <a href="../../other/HGPKLv1.html">HGPKL, Version 1</a>
</p>

</div>
</div>
