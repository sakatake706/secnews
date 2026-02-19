- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-02-19

- **タイトル**
Microsoft Entraアカウント狙うデバイスコード詐欺

- **概要**
攻撃者はOAuth 2.0デバイス認証フローを悪用し、正規のMicrosoft OAuthクライアントIDを使って被害者を騙し認証させる手口を用いる。この手法により有効な認証トークンを取得し、パスワードや多要素認証コードを盗まずにアカウントへ不正アクセス可能となる。攻撃は技術、製造、金融分野を標的とし、被害拡大の恐れがある。

- **URL**
https://www.bleepingcomputer.com/news/security/hackers-target-microsoft-entra-accounts-in-device-code-vishing-attacks/

- **備考**
攻撃者は正規のOAuthアプリを悪用し、デバイスコード詐欺を通じてMicrosoft Entraアカウントの認証トークンを不正取得する。これにより多要素認証を回避し、企業のクラウドサービスへアクセス可能となる。対策としてOAuthアプリの監査、疑わしい認証イベントの監視、不要なデバイスコードフローの無効化が推奨される。将来的に類似手法の拡大が懸念される。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[IT]]

- **攻撃手口**
[[標的型攻撃]]

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
OAuthアプリ監査、認証ログ監視、デバイスコードフロー無効化

- **ハッシュタグ**
#MicrosoftSecurity #OAuthAttack #Vishing
