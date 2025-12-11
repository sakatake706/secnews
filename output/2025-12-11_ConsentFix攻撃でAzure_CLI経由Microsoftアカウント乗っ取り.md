- **収集元サイト**
Bleepingcomputer

- **掲載日**
2025-12-11

- **タイトル**
ConsentFix攻撃でAzure CLI経由Microsoftアカウント乗っ取り

- **概要**
ConsentFix攻撃はAzure CLIのOAuth認証コードを悪用しパスワードや多要素認証を回避してMicrosoftアカウントを乗っ取る手法である。攻撃者は偽のCloudflare CAPTCHAを用い標的ユーザーを誘導し認証コードを盗み出す。これにより正規のログイン情報なしでアカウント制御が可能となるため被害拡大の恐れがある。

- **URL**
https://www.bleepingcomputer.com/news/security/new-consentfix-attack-hijacks-microsoft-accounts-via-azure-cli/

- **備考**
ConsentFix攻撃はOAuth認証コードを狙い標的ユーザーを偽の認証画面に誘導する。攻撃者はAzure CLIの認証コードを奪いパスワードや多要素認証を回避してアカウントを制御する。検知には異常なAzure CLIログイン監視が有効であり早期発見と対策が重要である。攻撃は標的限定で実行され被害拡大の可能性が高い。攻撃手法の理解と対策強化が求められる。攻撃者[[不明]]、攻撃手法[[ConsentFix]]。

- **分類**
[[注意喚起]]

- **組織名**
N/A

- **業種**
[[IT]]

- **攻撃手口**
[[標的型攻撃]]

- **攻撃影響**
N/A

- **脅威アクター**
[[不明]]

- **原因**
N/A

- **対処方法**
多要素認証強化、異常ログイン監視、ユーザー教育、アクセス制御強化

- **ハッシュタグ**
#ConsentFix #AzureCLI #セキュリティ
