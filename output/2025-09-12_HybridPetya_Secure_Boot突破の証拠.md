- **収集元サイト**
The Register

- **掲載日**
2025-09-12

- **タイトル**
HybridPetya Secure Boot突破の証拠

- **概要**
新たなランサムウェアHybridPetyaはUEFI Secure Bootの脆弱性を悪用しWindowsシステムを攻撃する。これは既知の4つ目のブートキットであり、MBR上書きによるディスクロック機能を持つ。現時点では実害報告はなくPoC段階だが、将来的な脅威として注視が必要である。

- **URL**
https://go.theregister.com/feed/www.theregister.com/2025/09/12/hopefully_just_a_poc_hybridpetya/

- **備考**
HybridPetyaはUEFI脆弱性[[CVE-2024-7344]]を利用し、EFIシステムパーティションに悪意あるアプリケーションを設置する。暗号化はNTFSのMFTを対象とし、被害者の個別鍵から復号鍵を再構築可能である。攻撃はディスク暗号化と偽CHKDSK表示を伴い、ランサムウェアとしての機能を持つ。対策はパッチ適用と監視強化が重要である。

- **分類**
[[脅威トレンド]]

- **組織名**
N/A

- **業種**
[[その他]]

- **攻撃手口**
N/A

- **攻撃影響**
N/A

- **脅威アクター**
[[N/A]]

- **原因**
パッチ適用、監視強化、アクセス制御強化

- **対処方法**
#HybridPetya #UEFISecurity #ランサムウェア
