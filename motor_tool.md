### RobStrideRS02 ID書き込み、ファームウェアアップデート手順

- #### 書き込みツールのダウンロード
  - RobStrideのリポジトリから[ダウンロード](https://github.com/RobStride/MotorStudio/releases/tag/v1.0.2)
![](/Media/motor_tool(01).png)
  - ZIPファイル解凍して中の「motor_tool.exe」実行する。
![](/Media/motor_tool(2).png)
  - 初回起動時にWindowsの警告が出る。
![](/Media/motor_tool(3).png)
  - ホーム画面。

- #### 準備
![](/Media/motor_tool(10).jpg)
- 準備物
  - モーター
  - モータ付属のモーター接続ケーブル
  - 充電器付属のXT60→TypeCケーブル
  - RT製電源ハブ基板
  - RobStride書き込み基板
  - 接続用ジャンパ線
![](/Media/motor_tool(11).jpg)
![](/Media/motor_tool(12).jpg)
![](/Media/motor_tool(13).jpg)

接続は上記写真を参考に行ってください。
- #### PCからモーターへアクセス
![](/Media/motor_tool(4).png)
  - 言語を中文から英語へ変更する。
![](/Media/motor_tool(5).png)
  - ①モーター、書き込み基板等をすべて接続したあと「RefreshCOM」をクリックすると上のボックスに接続されたCOMPortが表示される。
②「Open Serial Port」をクリックして電源につないだケーブルを一度抜き挿しするとCANのIDが表示される。
![](/Media/motor_tool(6).png)
- 「RefreshPara Table」をクリックするパラメーターの一覧が表示される。


- #### CANIDの書き込み
![](/Media/motor_tool(8).png)
- ①左の操作パネル「Motor Configration」の「Set ID」横の数字をクリックし書き込みたい数字を入力する。
- ②「Set ID」をクリック
- ③「RefreshPara Table」をクリックするとテーブルが更新されてIDの変更が確認できる。

- #### ファームウェアの書き換え
![](/Media/motor_tool(7).png)
- [サイト](https://github.com/RobStride/Product_Information/releases)からファームウェア[「rs02_0.2.3.24.bin」](https://github.com/RobStride/Product_Information/releases/download/V25.12.09/rs02_0.2.3.24.bin)をダウンロードする。
![](/Media/motor_tool(9).png)
- 操作パネル左の「OAT」からはじめに「erase」をクリックする。
- 「open file」をクリックし、先ほどダウンロードしたbinファイルを選択して開く
- 「start update」をクリックするとアップデートが開始する。緑のゲージが100％まで到達するとアップデート完了する。
