# control_board

体験演習，設計製作論１，設計製作論２用の制御ボードを設計・製作する．

### テキスト

[240422_mbed_手引.pdf](https://github.com/yasuohayashibara/control_board/files/15056090/240422_mbed_.pdf)

### 製作動画（参考）

- 制御回路の製作  
https://youtu.be/l_31r6Y3-js

### ソフトウェア開発用プロジェクトのテンプレート

- オフライン(KEIL)  
[adrobo_template_uvision6_nucleo_f303k8.zip](https://github.com/yasuohayashibara/control_board/files/4907584/adrobo_template_uvision6_nucleo_f303k8.zip)

- オンライン  
https://os.mbed.com/teams/adrobo/code/adrobo_template/

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

### 回路図　2024年度版(24/04/22修正)
![schematic](https://github.com/yasuohayashibara/control_board/assets/5755200/444a64f6-9bbe-4630-acca-5f8785c4ac26)

### PCB (80mm x 60mm)　2024年度版(24/04/22修正）
![board](https://github.com/yasuohayashibara/control_board/assets/5755200/bb7fa9a7-ca51-4a74-961c-f0a691e511e5)

### 試作した基板 (80mm x 60mm)　第２次試作
![試作した基板](https://user-images.githubusercontent.com/5755200/78966498-04151980-7b3b-11ea-8ee4-95559a45fb45.jpg)

### 試作した電子回路 (80mm x 60mm)　第２次試作
![試作した電子回路](https://user-images.githubusercontent.com/5755200/79032034-36c41e00-7bde-11ea-87bd-a8abc72cf661.jpg)

### 開発の経緯
https://github.com/yasuohayashibara/control_board/issues?q=is%3Aissue

### ピンアサイン
NUCLEO-F303K8  
https://os.mbed.com/platforms/ST-Nucleo-F303K8/
![ピンアサイン](https://os.mbed.com/media/uploads/bcostm/nucleo_f303k8_2017_10_10.png)

### 部品リスト
品名 | 型番 | 個数 | 単価 | 価格 | 販売元
-- | -- | -- | -- | -- | --
コンピュータ | NUCLEO-F303K8 | 1 | 1605 | 1605 | digikey
モータドライバ | L293B※1 | 1 | - | - | digikey
インバータ | TC74HC04APF | 1 | 30 | 30 | 秋月
レギュレータ | LM2940T-5.0 | 1 | 60 | 60 | digikey
汎用ダイオード | 1SS270A | 5 | 3 | 15 | 秋月
ツェナーダイオード | 1N5226B | 1 | 5 | 5 | 秋月
ファーストリカバリダイオード | ERA22-04V3 | 8 | 5 | 40 | 秋月
抵抗 | 1kΩ, 1/6W | 11 | 1 | 11 | 秋月
積層セラミックコンデンサ | 0.1uF | 5 | 4.2 | 21 | 秋月
電解コンデンサ | 100uF | 1 | 3.5 | 3.5 | 秋月
LED | OSG8HA3Z74A | 5 | 6 | 30 | 秋月
タクトスイッチ |   | 2 | 8.8 | 17.6 | 秋月
ピンヘッダ | PSS-430256-05 | 2 | 19 | 38 | 廣杉
ピンヘッダ | PSS-430256-04 | 1 | 17 | 17 | 廣杉
コネクタ | B2B-XH-A | 3 | 10 | 30 | 秋月
コネクタ | XHP-2 | 3 | 5 | 15 | 秋月
コンタクト | SXH-001T-P0.6 | 6 | 2 | 12 | 秋月
電池ボックス | SBH-341-1AS | 1 | 110 | 110 | 秋月
基板 |   | 1 | 253 | 253 | P板
ICソケット | 16P | 1 | 10 | 10 | 秋月
ICソケット | 14P | 1 | 10 | 10 | 秋月
ピンソケット（メス） | 1x15 | 2 | 40 | 80 | 秋月
  |   |   |   |   |  
合計 |   |   |   | - |  
コンピュータを除いた合計 |   |   |   | - |  

※１　L293Eを使用していましたが，入手が困難になったため現在モータドライバを再選定中

### 謝辞
本開発はSTマイクロエレクトロニクス(株)のユニバーシティ・プログラムにご支援いただいております．  
この場を借りて感謝の意を表します．  
https://www.stmcu.jp/university/
