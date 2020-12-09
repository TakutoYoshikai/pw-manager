# pw-manager

### 使い方
You should use this after you copy this repository to your private repository because destination to save is github repository.

Account information is encrypted.

You have to register password for using this.

### Prerequisites
* Ubuntu 20.04

### Requires
* srm
* openssl

```
#保存領域作成
password new

#マスターパスワード変更
password change

#全てのアカウント情報を表示
password show

#githubにバックアップ
password save

#アカウント追加
password register <service name>

#メールアドレス取得
password <service name> -email

#パスワード取得
password <service name> -pw
```
