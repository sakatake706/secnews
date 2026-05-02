- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-05-02

- **タイトル**
ConsentFix v3攻撃Azure標的化

- **概要**
ConsentFix v3はOAuth認証コードの悪用によりMicrosoft Azure環境を標的とする新たな攻撃手法である。攻撃者はAzureのテナントIDを確認後、従業員情報を収集し複数のアカウントを作成してフィッシングやデータ収集を行う。Pipedreamを用いた自動化により認証コードを即座にトークンに交換し、被害拡大を図る。攻撃は正規のMicrosoftログインフローを模倣し多要素認証を回避する点が特徴である。

- **URL**
https://www.bleepingcomputer.com/news/security/consentfix-v3-attacks-target-azure-with-automated-oauth-abuse/

- **備考**
ConsentFix v3はOAuth認証コードの悪用によりMicrosoft Azure環境を標的としPipedreamを活用した自動化で攻撃効率を高める。攻撃者は従業員情報を収集し複数アカウントを作成してフィッシングやデータ収集を実施。推奨対策はトークンバインディング設定行動検知ルール適用アプリ認証制限強化である。将来的に類似攻撃の拡大が懸念される。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[IT]]

- **攻撃手口**
[[フィッシング]]

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
トークンバインディング設定、行動検知ルール適用、アプリ認証制限強化

- **ハッシュタグ**
#OAuth #Azure #フィッシング
