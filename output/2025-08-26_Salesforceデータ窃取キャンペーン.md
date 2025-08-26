- **収集元サイト**
Threat Intelligence

- **掲載日**
2025-08-26

- **タイトル**
Salesforceデータ窃取キャンペーン

- **概要**
UNC6395がSalesloft DriftのOAuthトークンを悪用し複数のSalesforceインスタンスから大量のデータを窃取した。主に認証情報を狙いAWSキーやパスワードが対象となった。ログは削除されていないため調査可能である。

- **URL**
https://cloud.google.com/blog/topics/threat-intelligence/data-theft-salesforce-instances-via-salesloft-drift/

- **備考**
Salesloft Driftを利用する組織は直ちに認証情報の見直しとキーの無効化を行うべきである。ログの確認と被害範囲の特定も推奨される。

- **分類**
[[他組織インシデント]]

- **組織名**
Salesforce

- **業種**
[[情報通信業]]

- **攻撃手口**
[[標的型攻撃]]

- **攻撃影響**
認証情報窃取と大量データ流出

- **脅威アクター**
[[UNC6395]]

- **原因**
OAuthトークンの悪用

- **対処方法**
不明

- **ハッシュタグ**
アクセストークン無効化、アプリケーション削除、認証情報のローテーション、ログ監査
