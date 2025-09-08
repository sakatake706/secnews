- **収集元サイト**
セキュリティ対策Lab

- **掲載日**
2025-09-07

- **タイトル**
SalesforceとSalesloft連携攻撃解説

- **概要**
2025年8月、Salesloftのチャット製品Driftを起点にOAuthトークンが悪用される大規模なサプライチェーン攻撃が発生した。攻撃者は正規権限で複数企業のSalesforceからサポートケース情報を抽出し、機密情報探索も試みた。影響企業はCloudflareやPalo Alto Networksなど著名企業が含まれ、全トークンの失効と連携再点検が急務となっている。

- **URL**
https://rocket-boys.co.jp/security-measures-lab/salesforce-salesloft-drift-supply-chain-cyberattack/

- **備考**
攻撃者はDriftのOAuthトークンを窃取し正規権限でSalesforce APIにアクセスした。これによりサポートケース情報の大量抽出が可能となり、影響は数百社に及ぶ。対策として全連携トークンの失効とローテーション、連携機能の遮断が推奨される。将来的な類似攻撃防止にはSSPMの活用やIOCハンティングが重要である。攻撃者はUNC6395として追跡されている。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[IT]]

- **攻撃手口**
[[標的型攻撃]]

- **攻撃影響**
限定的な顧客情報流出

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
トークン失効、連携遮断、SSPM導入、IOCハンティング強化

- **ハッシュタグ**
#サプライチェーン攻撃 #OAuthトークン #Salesforce
