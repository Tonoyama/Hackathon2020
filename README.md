# ハッカソン2020
研究室の入退室管理システムを開発する大学のハッカソン。

## 動画

## 概要
PaSoRi(カードリーダ)で学籍番号を読取り、入退室の有無を判定、ラズパイからGASに送信。GASでスプレッドシートに入退室を記録。夜にメール、Slackへ１日分の入退室記録を送信する。

## スクリプト
### ラズパイに設置するPythonフォルダ
https://github.com/yasyasyu/Phackathon2020/tree/main/test

### PaSoRi(カードリーダ)で学籍番号を読取り入退室の有無を判定するスクリプト
https://github.com/yasyasyu/Phackathon2020/blob/main/test/scan.py

### ラズパイからGASへ入退室記録を送信するスクリプト
https://github.com/yasyasyu/Phackathon2020/blob/main/test/send.py

### メールに入退室記録を送信するスクリプト
https://github.com/shintaro129/pHackathonGAS/blob/main/sendToMail.js

### Slackに入退室記録を送信するスクリプト
https://github.com/shintaro129/pHackathonGAS/blob/main/sendToSlack.js

### 当日分の入退室記録を取得するスクリプト
https://github.com/shintaro129/pHackathonGAS/blob/main/todayDateSelect.js

### ラズパイの時刻同期と再起動の設定
https://hackmd.io/@T7k0V7TMQFelvJKKdo3pww/BJhFl2zqw

## 概要図
