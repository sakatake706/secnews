- **収集元サイト**
Bleepingcomputer

- **掲載日**
2025-08-25

- **タイトル**
Critical Docker flaw allows hijack

- **概要**
Docker Desktopの重大な脆弱性により悪意あるコンテナがホストシステムを乗っ取る可能性がある。特にWindows環境でDocker Engine APIへの認証なしアクセスが可能であり、ファイルの不正読み取りやシステムDLLの上書きによる権限昇格が懸念される。macOSではユーザー許可が必要なため被害は限定的だが完全な安全とは言えない。対策版Docker Desktop 4.44.3がリリース済みである。

- **URL**
https://www.bleepingcomputer.com/news/security/critical-docker-desktop-flaw-lets-attackers-hijack-windows-hosts/

- **備考**
Docker Desktopの脆弱性は[[CVE-2025-9074]]であり、攻撃者は認証不要でAPIにアクセスし悪意あるコンテナを起動可能だ。WindowsではWSL2経由でファイルシステム全体をマウントし管理者権限を奪取できる。macOSはユーザー許可が障壁となるが完全防御ではない。迅速なパッチ適用が必須であり、類似の[[SSRF]]攻撃にも注意が必要だ。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
N/A

- **攻撃手口**
[[ランサムウェア]]

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
パッチ適用、Docker Desktop更新、アクセス制御強化、監視体制整備

- **ハッシュタグ**
#Docker #脆弱性 #セキュリティ
