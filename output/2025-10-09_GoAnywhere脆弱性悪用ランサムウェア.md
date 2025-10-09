- **収集元サイト**
セキュリティ対策Lab

- **掲載日**
2025-10-09

- **タイトル**
GoAnywhere脆弱性悪用ランサムウェア

- **概要**
FortraのGoAnywhere Managed File Transferに存在するCVE-2025-10035の脆弱性がStorm-1175により2025年9月11日以降悪用されている。攻撃はライセンスServletの署名検証回避から任意オブジェクト反序列化を経てRCEに至る。攻撃者はRMMツールを用い永続化と横展開を実施し、Cloudflare TunnelでC2を隠蔽しつつMedusaランサムウェアを投入した。管理境界外のMFTは大規模流出と停止リスクを伴う。

- **URL**
https://rocket-boys.co.jp/security-measures-lab/ransomware-group-medusa-exploits-goanywhere-vulnerability-microsoft-report/

- **備考**
攻撃は認証不要でRCEに至り、RMM悪用とクラウドトンネル併用で検知回避が可能である。推奨対策は最新バージョンへの更新、ログの遡及確認、外向き通信の制限、EDRのブロックモード運用、ASMによる資産把握、資格情報の棚卸しとローテーション、RDPやRMM利用抑制である。将来的に類似攻撃の拡大が懸念されるため継続的監視が必要。

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
[[N/A]]

- **原因**
N/A

- **対処方法**
最新バージョン更新、ログ遡及確認、外向き通信制限、EDRブロックモード、ASM資産把握、資格情報棚卸しローテーション、RDP利用抑制

- **ハッシュタグ**
#Medusa #GoAnywhere #ランサムウェア
