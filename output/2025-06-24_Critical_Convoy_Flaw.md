- **収集元サイト**
GBHackers

- **掲載日**
2025-06-24

- **タイトル**
Critical Convoy Flaw

- **概要**
Performave ConvoyのKVM管理パネルに存在する重大脆弱性[[CVE-2025-52562]]により認証不要で任意コード実行が可能となる。攻撃者はHTTPパラメータの不適切な検証を悪用しディレクトリトラバーサルを行い、サーバー完全制御や機密情報窃取を実現する。対象バージョンは3.9.0-rc3から4.4.0であり、4.4.1で修正済みである。

- **URL**
https://gbhackers.com/critical-convoy-flaw/

- **備考**
[[CVE-2025-52562]]による認証不要のリモートコード実行脅威は深刻であり、攻撃者は不正HTTPリクエストを用いてシステム制御を奪取する。推奨対策は即時の4.4.1以上へのアップデート、WAFによる入力検証強化、異常なPHP実行やcronジョブの監視である。未対策環境はランサムウェアや情報漏洩被害拡大の危険性が高い。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[IT]]

- **攻撃手口**
[[ランサムウェア、マルウェア]]

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
即時アップデート、WAF導入、監視強化

- **ハッシュタグ**
#脆弱性 #リモートコード実行 #Convoy
