- **収集元サイト**
The Register

- **掲載日**
2025-09-18

- **タイトル**
CloudflareのDDoS障害原因

- **概要**
CloudflareのダッシュボードでReactのuseEffectフックの誤用によりAPIへの過剰な呼び出しが発生し、1時間以上のサービス停止を引き起こした。問題は依存配列内のオブジェクトが毎回再生成されることでフックが繰り返し実行されたためである。これによりAPIが過負荷となり障害が発生した。

- **URL**
https://go.theregister.com/feed/www.theregister.com/2025/09/18/cloudflare_ddosed_itself/

- **備考**
ReactのuseEffectフックの誤用が原因でAPIが過負荷となりサービス停止に至った。過剰なAPI呼び出しはDDoS攻撃のような影響を与え、Tenant Service APIの容量不足も問題を悪化させた。対策としてリソース増強と監視強化が実施され、API呼び出しの識別情報追加により問題特定が容易となった。今後は依存配列の管理徹底が必要である。

- **分類**
[[他組織インシデント]]

- **組織名**
Cloudflare

- **業種**
[[IT]]

- **攻撃手口**
[[その他]]

- **攻撃影響**
サービス停止により利用者に影響発生

- **脅威アクター**
[[N/A]]

- **原因**
ReactのuseEffectフックの誤用によるAPI過負荷

- **対処方法**
リソース増強、監視強化、依存配列管理徹底

- **ハッシュタグ**
#Cloudflare #React #DDoS
