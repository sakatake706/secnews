- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-06-18

- **タイトル**
Klue OAuth侵害とIcarus攻撃

- **概要**
市場情報プラットフォームKlueのOAuth侵害により、脅威アクター[[Icarus]]が複数組織のSalesforce CRMデータを窃取し、継続的な恐喝キャンペーンを展開している。攻撃者はOAuthトークンを悪用し、API経由でデータを抽出した。被害組織は連携アプリの利用停止やトークンの無効化を実施中である。

- **URL**
https://www.bleepingcomputer.com/news/security/klue-oauth-breach-linked-to-icarus-salesforce-data-theft-attacks/

- **備考**
攻撃者はKlueのBattlecards統合サービスアカウントを乗っ取り、OAuthトークンを用いてSalesforce環境からデータを抽出した。攻撃は段階的に行われ、初期は偵察的に対象データを特定し、後に大量のクエリで迅速にデータを窃取した。[[Icarus]]は比較的新しい恐喝グループであり、被害者に対しセッションメッセンジャーを通じた恐喝メールを送付している。対策としてはOAuthトークンの無効化、APIアクセスログの監視、連携アプリの停止が推奨される。今後も類似攻撃の拡大が懸念される。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[産業分類]]

- **攻撃手口**
[[標的型攻撃]]

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
OAuthトークン無効化、APIログ監視、連携アプリ停止

- **ハッシュタグ**
#Klue #Icarus #Salesforce
