- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-04-06

- **タイトル**
GPUBreach攻撃でGPU権限昇格可能

- **概要**
GPUBreach攻撃はGPUのGDDR6メモリに対するRowhammerビットフリップを利用し、GPUページテーブルを破損させて任意のメモリ読み書きを実現する。これにより、CUDAカーネルの権限を悪用し、NVIDIAドライバのメモリ安全性の欠陥を突いてCPU側の権限昇格を誘発し、IOMMU保護を無効化せずにシステム全体の制御を奪取可能である。研究成果はIEEE Symposiumで発表予定。https://www.bleepingcomputer.com/news/security/new-gpubreach-attack-enables-system-takeover-via-gpu-rowhammer/

- **URL**
GPUBreachはGPUのRowhammer攻撃を進化させ、単なるデータ破損を超えた権限昇格を可能にする。攻撃者はGPUメモリの読み書きを悪用し、ドライバの脆弱性を連鎖的に利用して完全なシステム制御を獲得する。IOMMU単独の防御は不十分であり、ECCメモリの有効化やシステムレベルのエラー訂正コードの導入が推奨される。将来的にはGPU関連の脆弱性対策強化が必要となる。[[GPUBreach]]攻撃の高度な技術的特徴と影響を詳細に分析。

- **備考**
[[他組織インシデント]]

- **分類**
N/A

- **組織名**
[[IT]]

- **業種**
[[標的型攻撃]]

- **攻撃手口**
N/A

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
システムレベルエラー訂正コード有効化、ドライバ更新、GPUメモリ保護強化

- **対処方法**
#GPUBreach #Rowhammer #GPU攻撃
