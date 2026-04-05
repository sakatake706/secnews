- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-04-05

- **タイトル**
React2Shell自動認証情報窃取攻撃

- **概要**
攻撃者はReact2Shell脆弱性を悪用しNextjsアプリを標的に自動化された認証情報窃取キャンペーンを展開した。766台のホストが侵害されデータベースやクラウド認証情報が抽出された。攻撃はNEXUS Listenerフレームワークを用い複数段階のスクリプトで秘密情報を収集し外部に送信する。被害は広範囲に及びシステム管理者は迅速な対策が必要である。

- **URL**
https://www.bleepingcomputer.com/news/security/hackers-exploit-react2shell-in-automated-credential-theft-campaign/

- **備考**
攻撃は自動スキャンで脆弱なNextjsアプリを特定しReact2Shell脆弱性を利用する。NEXUS Listenerを介し収集した認証情報はクラウドアカウント乗っ取りや横展開に悪用される可能性が高い。対策としてReact2Shellのセキュリティ更新適用、認証情報の即時ローテーション、AWS IMDSv2の強制、WAFやRASPの導入、最小権限の徹底が推奨される。将来的に類似攻撃の拡大が懸念される。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[産業分類]]

- **攻撃手口**
[[ランサムウェア]]

- **攻撃影響**
N/A

- **脅威アクター**
[[N/A]]

- **原因**
N/A

- **対処方法**
React2Shell更新適用、認証情報ローテーション、AWS IMDSv2強制、WAF導入、最小権限徹底

- **ハッシュタグ**
#React2Shell #認証情報窃取 #NEXUSListener
