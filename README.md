## 電卓(GUI)
開発者  
- 鈴木 健吾

#### システム概要  
数字キーと四則演算、Enter、CLのみの整数電卓

#### 開発経緯  
Go言語を学び、フレームワークのGinなども触ってみたところ、GUIアプリケーションを作成してみたいと考え、Fyneを用い電卓アプリケーションの実装を行った。電卓を選んだ理由は、普段自分がよく使うGUIアプリケーションは電卓であり、自身で実装することで、その中身や動作がどういった原理・仕組みで動いているかを理解したかったためである。  


#### 機能要件  
|機能|内容|
|:--|:--|
|数字入力|入力したい整数値を設定可能|
|四則演算|入力した整数値を用いて四則演算が可能|
|CL|実行・入力している計算をリセットすることが可能|


#### 開発環境
##### 言語
- Go

#### 実行方法
該当フォルダで「go run calculator.go」と入力及び「.\calculator.exe」で実行可能。



## ディレクトリ構成
<pre>
.
├── README.md
├── calculator.exe
└── calculator.go

</pre>
