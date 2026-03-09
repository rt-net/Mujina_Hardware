### ファームウェアの書き込み
   USB出力9軸IMUセンサモジュールV3と「WeAct」USB-CANFDインタフェースは下記リンクを参考の上、ファームウェアの書き込み後に機体へ組み込んでください。
- #### [「USB出力9軸IMUセンサモジュールV3」](https://github.com/rt-net/rt-usb-9axis-imu3-stm32duino-fw)ファームウェアリポジトリ
  - 書き込むバイナリファイルは[こちら](https://github.com/rt-net/rt-usb-9axis-imu3-stm32duino-fw/releases)です。
  - 書き込みツール
    - STM32CubeProg
- #### [USB-CANFDインタフェース](https://github.com/rt-net/candleLight_fw)ファームウェアリポジトリ
  - 書き込むバイナリファイルは[こちら](https://github.com/rt-net/candleLight_fw/releases/tag/v0.1.0-WeActStudio_USB2CANFDV1)です。
  - 書き込みツール
    - STM32CubeProg
    - 「ST-Link V2」もしくは「ST-Link V3」
    - ※ファームウェア書き込む事前作業としてFlashを空にする必要があります。こちらはWeActStudioのGithubのREADME[「How to completely empty Flash」](https://github.com/WeActStudio/WeActStudio.USB2CANFDV1?tab=readme-ov-file#how-to-completely-empty-flash)をご参照ください。