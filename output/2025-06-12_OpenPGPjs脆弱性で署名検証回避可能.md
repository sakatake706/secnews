- **収集元サイト**
GBHackers

- **掲載日**
2025-06-12

- **タイトル**
OpenPGPjs脆弱性で署名検証回避可能

- **概要**
OpenPGPjsの脆弱性により攻撃者がメッセージ署名検証を回避できる問題が発見された。この脆弱性は署名付きメッセージに悪意あるパケットを追加する手法で、正当な署名がある場合でも改ざんされた内容が有効と認識される。影響範囲はバージョン5.0.1から5.11.2および6.0.0-alpha.0から6.1.0であり、4.xは対象外である。修正パッチが公開されている。

- **URL**
https://gbhackers.com/openpgp-js-vulnerability-allows-attackers/

- **備考**
OpenPGPjsの脆弱性はメッセージの整合性を破壊し攻撃者が改ざんメッセージを正当と偽装可能である。攻撃は署名付きメッセージに悪意あるパケットを追加する手法で実施される。推奨対策は速やかなバージョンアップと署名検証の分離処理である。将来的に類似の署名検証回避攻撃が増加する可能性が高く、継続的な監視と対策強化が必要である。攻撃者[[不明]]の手法である。

- **分類**
[[脅威トレンド]]

- **組織名**
N/A

- **業種**
[[その他]]

- **攻撃手口**
N/A

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
ソフトウェア更新、署名検証分離、監視強化

- **対処方法**
#OpenPGPjs #脆弱性 #セキュリティ
