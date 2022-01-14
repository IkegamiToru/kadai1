# ラズパイ用デバドラ(LED点消灯)
上田先生の講義動画通りにラズパイのためのデバイスドライバを作りました。LEDをGPIO25とGNDにつなぎ、ターミナルにて`echo 1 > /dev/myled0`と入力するとLEDが点灯、`echo 0 > /dev/myled0`と入力すると消灯するプログラムです。

## インストール方法
このリポジトリをforkして`git clone`でcloneして使用してください。

## 使用方法
`$ cd kadai1`  
LEDの点灯
`$ echo 1 > /dev/myled0`  
LEDの消灯
`$ echo 0 > /dev/myled0`  

## デモ動画
実際に動いているところを下記のリンクより確認できます。  
[課題1の動画](https://youtu.be/sSezWMWWlZM)

## 参考動画、参考リンク
[ロボットシステム学第7回～第8回(Youtube)](https://www.youtube.com/watch?v=xQW8-FNuboo)  
[ロボットシステム学の練習用デバイスドライバ(GitHub)](https://github.com/ryuichiueda/robosys_device_drivers)

## 著作者
上田隆一

## ライセンス
このプロジェクトはGPLライセンスに基づいています。
