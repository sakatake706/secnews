- **収集元サイト**
セキュリティ対策Lab

- **掲載日**
2025-07-16

- **タイトル**
FortiWebFabricConnectorの脆弱性

- **概要**
Fortinet製WebアプリケーションファイアウォールFortiWebのFabricConnectorに認証バイパスを伴うSQLインジェクション脆弱性が存在する。これにより攻撃者は事前認証で任意コード実行が可能となる。複数の研究者が高精度なPoCを公開し、影響範囲は広範である。早急なパッチ適用が必要である。

- **URL**
https://rocket-boys.co.jp/security-measures-lab/furuno-electric-possible-personal-data-breach-of-1493-employees-and-client-information-due-to-unauthorized-server-access-2/

- **備考**
Fortinet製品のFabricConnectorに存在するSQLインジェクション脆弱性は認証バイパスを許し、リモートコード実行を可能とする。攻撃者はHTTPヘッダーを悪用し、MySQLのINTO OUTFILE機能を使ったファイル書き込みやPythonの.pth機構を悪用したコード実行を行う。対策としては管理インターフェースの遮断やログ監視、WAFによる特定パスのブロックが推奨される。今後の被害拡大の可能性が高く、迅速な対応が求められる。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[産業分類]]

- **攻撃手口**
[[脆弱性の悪用]]

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
管理インターフェース遮断、Authorizationヘッダー監視、WAFブロック、FabricConnector使用状況確認

- **ハッシュタグ**
#FortiWeb #SQLi #RCE
