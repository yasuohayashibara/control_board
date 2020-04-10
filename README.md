# control_board

体験演習，設計製作論１，設計製作論２用の制御ボードを設計・製作する．

### 仕様
- 電源電圧　4.8-9.0V
- LED x 5 (GPIO共用)
- SW x 2 
- モータ x 2　（電源Vcc）
- サーボモータ x 4　（電源Vcc）
- ADC x 5　（電源5V, 3.3V入力，保護回路追加）
- GPIO x 5　（電源5V, 5V tolerant，LED共用）

### 設計データ
https://drive.google.com/drive/folders/1z3KATSUruy6u5POwb1kSAXDd8bHVEIsI?usp=sharing

### 使用するコンピュータ
NUCLEO-F303K8  
https://www.st.com/ja/evaluation-tools/nucleo-f303k8.html

### 回路図
![schematic](https://user-images.githubusercontent.com/5755200/76876321-1d68d400-68b5-11ea-8c4b-60103e7d5fce.png)

### PCB (80mm x 60mm)　第２次試作（2020/03/30修正）
![PCB](https://user-images.githubusercontent.com/5755200/77907740-24d0aa00-72c5-11ea-968d-9c0dcea1982a.png)

### 試作した基板 (78mm x 60mm)　第２次試作
![試作した基板](https://user-images.githubusercontent.com/5755200/78966498-04151980-7b3b-11ea-8ee4-95559a45fb45.jpg)

### 試作した電子回路 (78mm x 60mm)　第１次試作
![試作した電子回路](https://user-images.githubusercontent.com/5755200/77592671-0752b780-6f36-11ea-9e7c-c03a013f7922.jpg)

### ピンアサイン
NUCLEO-F303K8  
https://os.mbed.com/platforms/ST-Nucleo-F303K8/
![ピンアサイン](https://os.mbed.com/media/uploads/bcostm/nucleo_f303k8_2017_10_10.png)

### 部品リスト
品名 | 型番 | 個数 | 単価 | 価格 | 販売元
-- | -- | -- | -- | -- | --
コンピュータ | NUCLEO-F303K8 | 1 | 1271 | 1271 | digikey
モータドライバ | L293E | 1 | 268 | 268 | digikey
インバータ | TC74HC04APF | 1 | 26 | 26 | digikey
レギュレータ | LM2940T-5.0 | 1 | 122 | 122 | digikey
汎用ダイオード | 1SS270A | 5 | 4 | 20 | 秋月
ツェナーダイオード | 1N5226B | 1 | 5 | 5 | 秋月
ファーストリカバリダイオード | ERA22-04V3 | 8 | 5 | 40 | 秋月
抵抗 | 1kΩ, 1/6W | 11 | 1 | 11 | 秋月
積層セラミックコンデンサ | 0.1uF | 5 | 15 | 75 | 秋月
電解コンデンサ | 100uF | 1 | 10 | 10 | 秋月
LED | OSG8HA3Z74A | 5 | 6 | 30 | 秋月
タクトスイッチ |   | 2 | 10 | 20 | 秋月
ピンヘッダ | PSS-430256-05 | 2 | 17 | 34 | 廣杉
ピンヘッダ | PSS-430256-04 | 1 | 15 | 15 | 廣杉
コネクタ | B2B-XH-A | 3 | 10 | 30 | 秋月
コネクタ | XHP-2 | 3 | 5 | 15 | 秋月
コンタクト | SXH-001T-P0.6 | 6 | 3 | 18 | 秋月
電池ボックス | SBH-341-1AS | 1 | 110 | 110 | 秋月
基板 |   | 1 | 393.82 | 393.82 | P板
ICソケット | 20P | 1 | 10 | 10 | 秋月
ICソケット | 14P | 1 | 10 | 10 | 秋月
ピンソケット（メス） | 1x15 | 2 | 40 | 80 | 秋月
  |   |   |   |   |  
合計 |   |   |   | 2613.8 |  
コンピュータを除いた合計 |   |   |   | 1342.8 |  
