---
title: "Rloginにicebergのカラースキームを導入する"
date: 2022-05-22T19:58:51+09:00
draft: false
---

普段自分はRloginを使っていますが、カラースキームにicebergが無かったので
作成しました。

## なぜiceberg?
- かっこいいから
- つよつよエンジニアがつかってそう(偏見)

## icerbergとは
vim用に開発されたカラースキームで世界中から人気があります。

## 導入方法
1. 設定用のエントリーを作成(タグも設定しておくと便利)
!["エントリー設定"](iceberg1.PNG)
1. カラーの`編集`をクリック
!["カラー設定"](iceberg2.PNG)
1. 下記の数値をコピーして右クリックで貼り付け
!["カラー設定"](iceberg3.PNG)
```
30	33	50
226	120	120
180	190	130
226	164	120
132	160	198
160	147	199
137	184	194
198	200	209
107	112	137
233	137	137
192	202	142
233	177	137
145	172	209
173	160	211
149	196	206
210	212	222
```

シンボリックリンクが見えづらい場合はシアンを変更してみてください。  
これでRloginにicebergの導入完了です。  
では良いターミナルライフを！