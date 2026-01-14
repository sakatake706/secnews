- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-01-14

- **タイトル**
FortiSIEM脆弱性公開

- **概要**
FortinetのFortiSIEMに存在するCVE-2025-25256は、認証不要でリモートから任意のコマンド実行を許す重大な脆弱性である。複数の問題が組み合わさり管理者権限での書き込みとroot権限昇格を可能にする。影響バージョンは6.7から7.5未満で、既に修正済みである。攻撃はphMonitorサービスの認証欠如が根本原因である。

- **URL**
https://www.bleepingcomputer.com/news/security/exploit-code-public-for-critical-fortisiem-command-injection-flaw/

- **備考**
FortiSIEMの脆弱性は認証不要のコマンド実行を許し、攻撃者は管理者権限を奪取可能である。攻撃手法はTCPリクエストを悪用し、phMonitorサービスの複数のコマンドハンドラを遠隔操作する。対策は速やかなパッチ適用とphMonitorポート制限であり、類似の脆弱性も過去に存在したため継続監視が必要である。攻撃者[[Black Basta]]の関心も高く被害拡大の恐れがある。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[産業分類]]

- **攻撃手口**
[[脆弱性の悪用]]

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
パッチ適用、phMonitorポート制限、監視強化

- **ハッシュタグ**
#FortiSIEM #脆弱性 #セキュリティ
