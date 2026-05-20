- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-05-20

- **タイトル**
YellowKey Windows脆弱性対策

- **概要**
MicrosoftはWindowsのBitLockerに関する新たなゼロデイ脆弱性[[YellowKey]]に対する緩和策を発表した。この脆弱性は特別に細工されたファイルを用いて保護されたドライブへのアクセスを可能にするものである。攻撃者はUSBドライブやEFIパーティションを利用し、WinRE起動時に特定の操作を行うことで権限を取得できる。Microsoftはこの問題をCVE-2026-45585として追跡し、既存の脆弱性対策と組み合わせた防御策を推奨している。

- **URL**
https://www.bleepingcomputer.com/news/microsoft/microsoft-shares-mitigation-for-yellowkey-windows-zero-day/

- **備考**
[[YellowKey]]はBitLocker保護ドライブへの不正アクセスを可能にし、攻撃者はUSBやEFIパーティションを介して権限昇格を狙う。推奨対策は自動起動ファイルの削除、BitLockerのTPM+PIN設定変更、グループポリシーによる追加認証設定である。これにより攻撃の成功率を大幅に低減できる。将来的には類似の脆弱性に対する迅速な対応が求められる。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[IT]]

- **攻撃手口**
[[脆弱性の悪用]]

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
自動起動ファイル削除、TPM+PIN設定変更、追加認証設定

- **ハッシュタグ**
#YellowKey #BitLocker #WindowsSecurity
