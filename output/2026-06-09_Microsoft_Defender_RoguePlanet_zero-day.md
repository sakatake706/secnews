- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-06-09

- **タイトル**
Microsoft Defender RoguePlanet zero-day

- **概要**
Microsoft Defenderの新たなゼロデイ脆弱性「RoguePlanet」はWindows10および11の最新パッチ適用環境に影響を与え、攻撃者がSYSTEM権限でコマンドプロンプトを起動可能とする競合状態の脆弱性である。攻撃成功率は環境により異なるが一部で100パーセントに達し、リモートコード実行の可能性も示唆されている。Microsoftは一部修正を施したが完全な防御策は未確立である。

- **URL**
https://www.bleepingcomputer.com/news/microsoft/microsoft-defender-rogueplanet-zero-day-grants-system-privileges/

- **備考**
攻撃者は競合状態を悪用しSYSTEM権限を奪取する手法を用いる。攻撃はリモートのSMB共有を介する可能性があり、検知困難なため被害拡大の恐れがある。対策としてはアプリケーション許可リストの活用や最新パッチ適用が必須である。将来的には類似の競合状態脆弱性が増加する可能性が高く、継続的な監視と迅速な対応が求められる。

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
アプリケーション許可リスト適用、最新パッチ適用、監視強化

- **ハッシュタグ**
#RoguePlanet #ゼロデイ #Microsoft
