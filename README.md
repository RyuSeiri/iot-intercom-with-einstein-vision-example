# 訪問者を識別するIoTインターホン powered by Einstein Vision

画像認識AI"Einstein Vision"の実装例のサンプルです。 呼び鈴はラズベリーパイで、受話器はSalesforceインターフェース上に、アプリケーションとして構築します。

※Einstein Vision 公式ドキュメント ⇒ <https://metamind.readme.io/v2/docs>

![アーキテクチャ全体](https://github.com/misu007/iot-intercom-with-einstein-vision-example/raw/master/img001.png)

## 準備するもの
* Raspberry Pi 3 Model B
* Raspberry Pi カメラモジュール
* Raspberry Pi Sense Hat

## 必要なアカウント
* Herokuアカウント ※サインアップ ⇒ <https://signup.heroku.com/>
* Salesforce Developer Edition組織のアカウント　※サインアップ ⇒ <http://developer.salesforce.com/signup>

## インストール
1. Salesforceの設定
ユーティリティバー上にLightning Component""を配置する。


2. Herokuの設定


3. Raspberry Piの設定
* Raspberry Pi Model B
* Raspberry Pi カメラモジュール
* Raspberry Pi Sense Hat
を組み立てる。

## 動作確認
1. Salesforceにログインし、画面を開いておく。

2. Raspberry Piのアプリケーションを起動する。
`npm start`

3. Raspberry Pi Sense Hat上のジョイスティックをクリックする。

4. Salesforce


## 免責事項
このサンプルコードは、あくまで機能利用の1例を示すためのものであり、コードの書き方や特定ライブラリの利用を推奨したり、機能提供を保証するものではありません。


