- **収集元サイト**
GBHackers

- **掲載日**
2025-06-11

- **タイトル**
CoreDNSのDoQに高リスク脆弱性が発見される

- **概要**
CoreDNSのDNS-over-QUIC実装において[[CVE-2025-47950]]の脆弱性が存在し攻撃者が無制限のQUICストリームを開きサーバーのメモリを枯渇させクラッシュを引き起こす可能性がある。パッチv1.21.2で修正されておりKubernetes環境で特に影響が大きい。

- **URL**
https://gbhackers.com/coredns-vulnerability/

- **備考**
この脆弱性はDoQのストリーム管理不備によるもので攻撃者は認証を回避し低帯域でサービス停止を狙う。対策としてパッチ適用やDoQ無効化リソース制限監視が推奨される。

- **分類**
[[注意喚起]]

- **組織名**
N/A

- **業種**
N/A

- **攻撃手口**
[[脆弱性の悪用]]

- **攻撃影響**
DNSサーバークラッシュによるサービス停止

- **脅威アクター**
N/A

- **原因**
[[CVE-2025-47950]]

- **対処方法**
設計上のストリーム制御不足

- **ハッシュタグ**
パッチ適用、DoQ無効化、リソース制限、監視強化
