- **収集元サイト**
GBHackers

- **掲載日**
2025-06-13

- **タイトル**
Microsoft Defender Spoofing Flaw Enables Privilege Escalation and AD Access

- **概要**
Microsoft Defender for Identityの新たな脆弱性[[CVE-2025-26685]]により認証されていない攻撃者が重要なディレクトリサービスアカウントのNet-NTLMハッシュを取得可能でActive Directory環境の侵害リスクがある。この脆弱性はMDIのLateral Movement Paths機能を悪用し2025年5月のパッチで対処済みである。

- **URL**
https://gbhackers.com/microsoft-defender-spoofing/

- **備考**
[[CVE-2025-26685]]の脆弱性は認証回避と権限昇格を狙いSMBの匿名接続を利用する。攻撃者はツールを用いてハッシュを取得しADCSの証明書発行を悪用し横展開を実施可能である。対策としてMDIのXDRセンサーへの移行やgMSAの利用推奨。過剰権限の監査とNTLMリレー防止が重要である。

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
N/A

- **原因**
N/A

- **対処方法**
MDIのXDRセンサー移行、gMSA利用、NTLMリレー防止、過剰権限監査

- **ハッシュタグ**
#脆弱性 #ActiveDirectory #セキュリティ
