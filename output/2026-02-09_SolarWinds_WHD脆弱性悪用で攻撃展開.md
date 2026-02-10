- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-02-09

- **タイトル**
SolarWinds WHD脆弱性悪用で攻撃展開

- **概要**
攻撃者はSolarWinds Web Help Deskの脆弱性を悪用し、正当なDFIRツールを悪用して攻撃を実行した。対象組織は少なくとも三つで、Cloudflareトンネルを用いた持続性確保やVelociraptorをC2に利用した。攻撃は2026年1月16日から開始され、複数の脆弱性を突いて遠隔コード実行を達成している。攻撃者はWindows Defender無効化やスケジュールタスクによるSSHバックドア設置も行った。

- **URL**
https://www.bleepingcomputer.com/news/security/threat-actors-exploit-solarwinds-wdh-flaws-to-deploy-velociraptor/

- **備考**
攻撃者は[[CVE-2025-40551]]や[[CVE-2025-26399]]を利用し、Zoho ManageEngine AssistやVelociraptorを悪用した。攻撃目的は持続的アクセス確保とコマンド制御であり、Windows Defender無効化やFirewall解除も実施された。推奨対策はSolarWinds WHDのアップデート、管理インターフェースの公開停止、認証情報のリセットである。類似事例としては過去の[[SolarWinds]]攻撃がある。将来的にはこうした正当ツール悪用の攻撃が増加する可能性が高い。

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
SolarWinds WHDアップデート、管理インターフェース非公開、認証情報リセット

- **ハッシュタグ**
#SolarWinds #脆弱性 #セキュリティ
