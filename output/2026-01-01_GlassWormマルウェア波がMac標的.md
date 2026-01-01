- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-01-01

- **タイトル**
GlassWormマルウェア波がMac標的

- **概要**
GlassWormマルウェアの第四波がmacOS開発者を狙い、悪意あるVSCode/OpenVSX拡張機能を通じてトロイ化された暗号通貨ウォレットを配布する。これらの拡張機能はGitHubやnpmの認証情報、暗号通貨ウォレットデータを盗み、VNC経由の遠隔操作やSOCKSプロキシを利用した通信経路の中継も可能にする。攻撃はAppleScriptとLaunchAgentsを用い持続性を確保し、Solanaブロックチェーンを使ったC2機能も維持されている。被害拡大の恐れがある。

- **URL**
GlassWormはmacOS専用に進化し、AES-256-CBC暗号化されたJavaScriptペイロードを用いる。攻撃者は開発者の認証情報やブラウザデータ、Keychainパスワードを狙い、Ledger LiveやTrezor Suiteの正規ハードウェアウォレットをトロイ化版に置換する機能も備える。対策として拡張機能の即時削除、パスワード変更、感染兆候の確認が必要である。将来的に攻撃の高度化と被害拡大が懸念される。

- **備考**
https://www.bleepingcomputer.com/news/security/new-glassworm-malware-wave-targets-macs-with-trojanized-crypto-wallets/

- **分類**
[[マルウェア]]

- **組織名**
[[他組織インシデント]]

- **業種**
N/A

- **攻撃手口**
[[マルウェア]]

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
拡張機能削除、パスワード変更、システム検査、再インストール

- **対処方法**
#GlassWorm #macOS #マルウェア
