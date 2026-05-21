- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-05-20

- **タイトル**
Hackers bypass SonicWall VPN MFA

- **概要**
攻撃者がSonicWall Gen6 SSL-VPN機器の未完全なパッチ適用を悪用し、多要素認証を回避した。侵入後30〜60分でネットワーク調査や資格情報の再利用を試みた。Gen6機器はファームウェア更新だけでは不十分でLDAPサーバの再設定が必須である。Gen7以降は更新のみで対策可能。攻撃は複数環境で確認されている。

- **URL**
https://www.bleepingcomputer.com/news/security/hackers-bypass-sonicwall-vpn-mfa-due-to-incomplete-patching/

- **備考**
攻撃者は有効な資格情報を用い[[CVE-2024-12802]]の脆弱性を突き多要素認証を回避した。侵入後はRDP接続やCobalt Strikeビーコンの展開を試みたがEDRに阻止された。LDAP設定の不備が根本原因であり、完全な再設定が推奨される。攻撃は自動化の兆候を示し、初期アクセスの売買も疑われる。対策は最新ファームウェア適用とLDAP再構築である。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[情報通信]]

- **攻撃手口**
[[標的型攻撃]]

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
LDAP再設定、最新ファームウェア適用、EDR強化

- **ハッシュタグ**
#SonicWall #VPN #セキュリティ
