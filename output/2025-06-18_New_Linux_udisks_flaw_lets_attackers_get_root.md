- **収集元サイト**
Bleepingcomputer

- **掲載日**
2025-06-18

- **タイトル**
New Linux udisks flaw lets attackers get root

- **概要**
二つの新規ローカル特権昇格脆弱性により主要Linuxディストリビューションでroot権限取得が可能となる。CVE-2025-6018はopenSUSE Leap 15とSUSE Linux Enterprise 15のPAM設定に存在し、allow_activeユーザー権限を奪取できる。CVE-2025-6019はlibblockdevのudisksデーモンに存在し、allow_activeユーザーがroot権限を取得可能である。これらの脆弱性は連鎖攻撃によりシステム完全制御を許すため即時対策が必要である。

- **URL**
https://www.bleepingcomputer.com/news/linux/new-linux-udisks-flaw-lets-attackers-get-root-on-major-linux-distros/

- **備考**
[[Qualys]]の調査によりroot権限取得を狙う[[CVE-2025-6018]]と[[CVE-2025-6019]]の脆弱性が判明。攻撃者はPAM設定とudisksデーモンの欠陥を悪用し、ほぼ全Linuxディストリビューションで権限昇格を達成可能。迅速なパッチ適用が推奨され、放置するとシステム全体の乗っ取りや持続的侵害のリスクが高まる。類似の過去脆弱性事例も存在し、今後も注意が必要である。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[IT]]

- **攻撃手口**
[[ランサムウェア]]

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
パッチ適用、権限管理強化、監視体制整備

- **ハッシュタグ**
#LinuxSecurity #脆弱性 #権限昇格
