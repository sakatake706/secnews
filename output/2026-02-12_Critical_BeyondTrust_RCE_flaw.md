- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-02-12

- **タイトル**
Critical BeyondTrust RCE flaw

- **概要**
BeyondTrust Remote SupportおよびPrivileged Remote Accessに存在する認証前リモートコード実行の脆弱性CVE-2026-1731が攻撃で悪用されている。影響を受けるバージョンはRemote Support 25.3.1以前およびPrivileged Remote Access 24.3.4以前である。攻撃者は特別に細工したリクエストを送信し、認証不要でシステムコマンドを実行可能であり、システム侵害やデータ流出、サービス妨害を引き起こす可能性がある。パッチ適用が急務である。

- **URL**
https://www.bleepingcomputer.com/news/security/critical-beyondtrust-rce-flaw-now-exploited-in-attacks-patch-now/

- **備考**
攻撃者は[[CVE-2026-1731]]の脆弱性を利用し、認証不要でリモートコード実行を行う。攻撃手法は特別に細工したクライアントリクエスト送信であり、被害拡大の恐れが高い。類似の[[RCE]]攻撃事例も多く、迅速なパッチ適用と監視強化が推奨される。将来的には自動化攻撃の増加も懸念される。

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
パッチ適用、監視強化、アクセス制御強化

- **ハッシュタグ**
#BeyondTrust #RCE #セキュリティ
