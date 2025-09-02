- **収集元サイト**
The Register

- **掲載日**
2025-09-02

- **タイトル**
Zscaler被害Salesloft攻撃顧客情報流出

- **概要**
ZscalerはSalesloft Drift攻撃により顧客データが流出した。攻撃は2025年8月8日から18日にかけて発生し、OAuthトークンの不正取得によりSalesforceの複数データが盗まれた。被害情報は名前やメールアドレス、役職、電話番号、地域情報、製品ライセンスや商用情報、サポートケースの一部テキストを含む。添付ファイルや画像は含まれていない。攻撃者は[[ShinyHunters]]と推定される。被害拡大の可能性があり注意が必要である。

- **URL**
https://go.theregister.com/feed/www.theregister.com/2025/09/02/zscaler_customer_data_drift_compromise/

- **備考**
攻撃者はSalesforce統合のOAuthトークンを悪用し大量の顧客情報を窃取した。攻撃は高度な[[SupplyChainAttack]]の一例であり、被害拡大防止にはトークンの無効化とアクセス権限の見直しが必須である。類似事例としてGoogleやPalo Alto Networksも被害を受けており、今後も同種攻撃の増加が懸念される。迅速なログ監査と異常検知体制の強化が推奨される。

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
[[ShinyHunters]]

- **原因**
N/A

- **対処方法**
Salesforce連携トークン無効化APIアクセス権限見直しログ監査強化

- **ハッシュタグ**
#Salesloft #データ流出 #サイバー攻撃
