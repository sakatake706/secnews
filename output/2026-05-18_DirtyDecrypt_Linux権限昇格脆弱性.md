- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-05-18

- **タイトル**
DirtyDecrypt Linux権限昇格脆弱性

- **概要**
Linuxカーネルのrxgkモジュールに存在するローカル権限昇格の脆弱性DirtyDecryptは、特定のLinuxシステムでroot権限取得を可能にする攻撃コードが公開された。この脆弱性はCONFIG_RXGKオプション有効時に影響し、FedoraやArch Linuxなど最新カーネルを使用するディストリビューションが対象である。攻撃はrxgk_decrypt_skbのCOWガード欠如に起因し、同様の脆弱性と共に注意が必要である。

- **URL**
https://www.bleepingcomputer.com/news/security/exploit-available-for-new-dirtydecrypt-linux-root-escalation-flaw/

- **備考**
DirtyDecrypt脆弱性はLinuxカーネルのrxgkモジュールに存在し、root権限昇格を可能にする。攻撃者はCONFIG_RXGK有効環境を狙い、FedoraやArch Linuxなど最新カーネルを使用するシステムが対象となる。攻撃手法はCOWガード欠如を利用し、既存の脆弱性と類似している。対策として最新カーネルの適用が必須であり、即時の更新が推奨される。将来的には同種の脆弱性が増加する可能性があり、継続的な監視と迅速な対応が必要である。攻撃者[[不明]]の活動が懸念される。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[産業分類]]

- **攻撃手口**
[[ランサムウェア]]

- **攻撃影響**
N/A

- **脅威アクター**
[[不明]]

- **原因**
N/A

- **対処方法**
最新カーネル適用、脆弱性監視強化、不要モジュール無効化

- **ハッシュタグ**
#DirtyDecrypt #LinuxSecurity #脆弱性
