# pw-manager

### 使い方
ご自身のプライベートリポジトリにコピーしてお使いください。

アカウント情報は暗号化して保存します。

暗号を解除するためにマスターパスワードを設定します。

githubに暗号化されたアカウント情報が保存されます。

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
