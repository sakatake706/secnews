- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-01-26

- **タイトル**
Hackers bypass npm defenses via Git dependencies

- **概要**
NPMのShai-Hulud防御策はGit依存関係を介して回避可能である。複数のJavaScriptパッケージ管理ツールに存在するPackageGate脆弱性により、悪意あるコード実行が許される。pnpmやvltは修正済みだがNPMは報告を拒否し対応遅延中である。攻撃は開発者秘密情報の大量流出を引き起こす危険がある。

- **URL**
https://www.bleepingcomputer.com/news/security/hackers-can-bypass-npms-shai-hulud-defenses-via-git-dependencies/

- **備考**
[[PackageGate]]脆弱性はGit依存関係の設定を悪用しスクリプト実行を回避する手法である。攻撃者はリバースシェル作成などの悪用を確認済みであり、NPMの対応遅延は被害拡大の懸念を増大させる。推奨対策は依存関係の厳格な検証、スクリプト無効化設定、二要素認証の徹底である。将来的には供給網全体のセキュリティ強化が必要となる。

- **分類**
[[脅威トレンド]]

- **組織名**
N/A

- **業種**
[[産業分類]]IT

- **攻撃手口**
[[マルウェア]]

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
依存関係検証、スクリプト無効化、二要素認証

- **ハッシュタグ**
#PackageGate #npm #セキュリティ
