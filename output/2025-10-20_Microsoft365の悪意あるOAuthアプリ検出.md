- **収集元サイト**
Bleepingcomputer

- **掲載日**
2025-10-20

- **タイトル**
Microsoft365の悪意あるOAuthアプリ検出

- **概要**
Huntress Labsが開発したCazadoraスクリプトはMicrosoft365環境内の悪意あるOAuthアプリを特定するためのツールである。調査により、AzureのEnterprise ApplicationsとApplication Registrationsに潜む攻撃に利用されるアプリの存在が明らかになった。これらのアプリは正規の認証と権限付与の仕組みを悪用し、攻撃者に初期アクセスを許す。特に「Traitorware」と呼ばれる正規アプリを悪用する手法と、カスタム作成された「Stealthware」アプリの存在が確認された。これらの脅威は多様な攻撃に利用され、検出が困難である。対策としては定期的なアプリ監査と異常検知の強化が必要である。

- **URL**
https://www.bleepingcomputer.com/news/security/find-hidden-malicious-oauth-apps-in-microsoft-365-using-cazadora/

- **備考**
Cazadoraスクリプトは攻撃者が悪用するOAuthアプリを検出し、初期アクセスの阻止に貢献する。攻撃者は正規の認証フローを悪用し、権限を取得しているため、検出が難しい。Traitorwareは正規アプリの悪用であり、Stealthwareはカスタム悪意アプリである。推奨対策は定期的な監査、異常な権限付与の検知、ユーザー教育である。将来的には検出技術の高度化と自動化が期待される。被害拡大の可能性は高く、早期対応が重要である。

- **分類**
[[注意喚起]]

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
アプリ監査強化、異常検知導入、ユーザー教育強化

- **ハッシュタグ**
#OAuth #Microsoft365 #セキュリティ
