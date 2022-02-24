# ネクストエンジンAPIのSDK(PHP)ミニマムサンプルコード
ネクストエンジンAPIのSDK(PHP)ミニマムサンプルコードです。
ネクストエンジンAPIに関してのリファレンスやコミュニティは[Developer Network](https://developer.next-engine.com/)をご利用ください。

## Description
SDKは以下のことが網羅されています。

- ネクストエンジンAPI利用時の認証関連処理
- ネクストエンジンAPI利用時のリクエスト処理
- サンプルリクエストロジック
詳細は[Developer Network](https://developer.next-engine.com/)を参照ください。

index.phpの以下の部分にネクストエンジンのアプリを作るで発行したクライアントID(CLIENT_ID)とクライアントシークレット(CLIENT_SECRET)をxxの部分に書き換えれば動作します。

```
define('CLIENT_ID','xxxxxxxxxxxx');
define('CLIENT_SECRET','xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx');
```

動作しない場合はphp-curlのパッケージがインストールされているか、ApacheまたはNginxのPHP読み込みの設定を見直してください

```
index.php = プログラムメイン(プログラム本体この部分を編集する)
neApiClient.php　=　SDk本体(編集する必要なし)
```

## Environment
推奨環境: PHP version 5.6 or greater
curl 7.25.0以降
