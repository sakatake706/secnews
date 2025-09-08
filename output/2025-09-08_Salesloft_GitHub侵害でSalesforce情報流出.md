- **収集元サイト**
Bleepingcomputer

- **掲載日**
2025-09-08

- **タイトル**
Salesloft GitHub侵害でSalesforce情報流出

- **概要**
2025年3月にSalesloftのGitHubリポジトリが侵害され、攻撃者はDriftのOAuthトークンを盗み出した。このトークンは8月にSalesforceの顧客データ窃取攻撃に悪用された。攻撃は複数の組織に影響を及ぼし、認証情報やアクセスキーの窃取を目的としていた。

- **URL**
https://www.bleepingcomputer.com/news/security/salesloft-march-github-repo-breach-led-to-salesforce-data-theft-attacks/

- **備考**
攻撃者はGitHub環境に不正アクセスし、複数のリポジトリからコードをダウンロード、ゲストユーザーを追加し不正なワークフローを作成した。DriftのAWS環境侵害によりOAuthトークンを奪取し、SalesforceやGoogle Workspaceの顧客データにアクセスした。対策として認証情報のローテーションや環境の分離が実施された。今後も類似の供給連鎖攻撃に注意が必要である。

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
[[Scattered Spider]]

- **原因**
GitHubリポジトリの不正アクセス、OAuthトークンの盗難、認証情報の流出

- **対処方法**
認証情報ローテーション、環境分離、脅威ハンティング強化

- **ハッシュタグ**
#Salesloft #SupplyChainAttack #OAuth
