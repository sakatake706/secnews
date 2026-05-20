- **収集元サイト**
Security Affairs

- **掲載日**
2026-05-20

- **タイトル**
DirtyDecryptによるLinuxカーネル脆弱性

- **概要**
新たなLinuxカーネルのローカル特権昇格脆弱性[[CVE-2026-31635]]のPoCが公開された。rxgk_decrypt_skb関数のCOWガード欠如により攻撃者がroot権限を取得可能である。過去の類似脆弱性に続く深刻な問題である。

- **URL**
https://securityaffairs.com/192436/uncategorized/dirtydecrypt-poc-released-for-yet-another-linux-flaw.html

- **備考**
この脆弱性はローカル攻撃者による権限昇格を許すため迅速なパッチ適用が必要でありシステム管理者は監視強化とアクセス制御の見直しを推奨する。

- **分類**
[[注意喚起]]

- **組織名**
N/A

- **業種**
N/A

- **攻撃手口**
[[脆弱性の悪用]]

- **攻撃影響**
root権限取得可能な脆弱性の公開

- **脅威アクター**
N/A

- **原因**
不明

- **対処方法**
パッチ適用、監視強化、アクセス制御見直し

- **ハッシュタグ**
#DirtyDecrypt #Linux脆弱性 #権限昇格
