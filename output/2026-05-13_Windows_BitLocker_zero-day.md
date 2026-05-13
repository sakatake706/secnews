- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-05-13

- **タイトル**
Windows BitLocker zero-day

- **概要**
サイバーセキュリティ研究者がWindowsのBitLockerに関する二つの未修正脆弱性を公開した。これらはBitLockerの保護を回避し、特権昇格を可能にするものである。特にYellowKeyはWindows Recovery Environmentに存在し、USBドライブやEFIパーティションを利用してシェルを起動し、暗号化ドライブへのアクセスを許す。GreenPlasmaはSYSTEM権限取得の可能性を持つ特権昇格脆弱性である。これらの脆弱性はTPM+PIN環境でも影響を及ぼす可能性があるが、PoCは限定的である。研究者は今後も未公開脆弱性の公開を示唆している。

- **URL**
https://www.bleepingcomputer.com/news/security/windows-bitlocker-zero-day-gives-access-to-protected-drives-poc-released/

- **備考**
[[YellowKey]]はBitLockerの自動解除機能を悪用し、Windows Recovery Environmentの脆弱性を突く攻撃である。[[GreenPlasma]]はSYSTEM権限取得を狙う特権昇格攻撃で、未完成のPoCが存在する。攻撃者はUSBやEFIパーティションを介して攻撃を実行可能であり、TPM+PIN環境でも影響が懸念される。対策としてBitLocker PIN設定やBIOSパスワードの利用が推奨される。将来的に類似の脆弱性公開が続く可能性が高い。

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
BitLocker PIN設定、BIOSパスワード設定、システムの最新更新適用、アクセス制御強化、監視体制の強化

- **ハッシュタグ**
#BitLocker #脆弱性 #セキュリティ
