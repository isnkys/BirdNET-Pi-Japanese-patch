<h1 align="center"><a href="https://github.com/mcguirepr89/BirdNET-Pi/blob/main/LICENSE">Review the license!!</a></h1>
<h1 align="center">You may not use BirdNET-Pi to develop a commercial product!!!!</h1>
<h1 align="center">
  BirdNET-Pi
</h1>
<p align="center">
  <img src="https://user-images.githubusercontent.com/60325264/140656397-bf76bad4-f110-467c-897d-992ff0f96476.png" />
</p>
<p align="center">
Icon made by <a href="https://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a>
</p>

## このフォークについて
データーベースの種名が日本語の場合、Daily plotの種名が文字化けを起こすのでフォントの設定を変更しました。一時的な処置のため今後も修正いたします。

そのほかの情報は以下のレポジトリを参照して下さい。

[achtzuster/BirdNET-Pi](https://github.com/Nachtzuster/BirdNET-Pi)

[mcguirepr89/BirdNET-Pi](https://github.com/mcguirepr89/BirdNET-Pi)

## はじめに
BirdNET-Piは、[**@kahst**](https://github.com/kahst) による[BirdNETフレームワーク](https://github.com/kahst/BirdNET-Analyzer)と[**@PINTO0309**](https://github.com/PINTO0309)による[事前構築されたTFLiteバイナリ](https://github.com/PINTO0309/TensorflowLite-bin)を基に構築されています。USBマイクまたはサウンドカードからの鳥の音をリアルタイムで認識し、そのデータを世界中と共有することができます。

世界中の鳥をチェックしましょう。
- [BirdWeather](https://app.birdweather.com)


## 必要なもの
* Raspberry Pi 5、Raspberry Pi 4B、Raspberry Pi 400、Raspberry Pi 3B+、または Raspberry Pi 0W2 （3B+ と 0W2 は RaspiOS-ARM64-**Lite** で動作必須）
* **_64ビット版のRaspiOS_** がインストールされたSDカード（Bookworm推奨）-- Liteが推奨されますが、RaspiOS-ARM64-Fullでもインストールは可能です。[Raspberry Pi Imager](https://www.raspberrypi.com/software/)内でダウンロード可能。
* USBマイクまたはサウンドカード


## インストール方法
[インストール方法はこちらのガイドをご覧ください。](https://github.com/mcguirepr89/BirdNET-Pi/wiki/Installation-Guide). 

以下のコマンドでインストールを行います:
```
curl -s https://raw.githubusercontent.com/isnkys/BirdNET-Pi-Japanese-patch/main/newinstaller.sh | bash
```

## アクセス方法
BirdNET-Piは、同じネットワーク上のウェブブラウザからアクセス可能です：
- http://birdnetpi.local 
- デフォルトユーザー名：birdnet
- パスワードはデフォルトでは空です。「Tool」>「Settings」>「Advanced settings」で設定してください。

## 種名の日本語化
- デフォルトでは英語です。「Tool」>「Settings」>「Localization」で 「Database Language:」を「Japanese」設定してください。

