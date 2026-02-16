- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-02-15

- **タイトル**
ClickFix攻撃でDNS経由PowerShellペイロード取得

- **概要**
ClickFix攻撃はDNSクエリを悪用し、攻撃者が制御するDNSサーバーからPowerShellペイロードを取得させる新手法を用いる。この攻撃はユーザーにnslookupコマンドを実行させ、DNS応答内の悪意あるスクリプトを実行させる。これにより、通常のHTTP経由とは異なりDNS通信を利用したマルウェア配布が可能となる。最終的にModeloRATが感染端末にインストールされ遠隔操作が可能となる。

- **URL**
https://www.bleepingcomputer.com/news/security/new-clickfix-attack-abuses-nslookup-to-retrieve-powershell-payload-via-dns/

- **備考**
ClickFix攻撃はDNSを利用した新たな手法でマルウェア配布を行う。攻撃者はnslookupコマンドを悪用し、DNS応答に含まれるPowerShellスクリプトを実行させることで感染を成立させる。これにより検知回避が可能となり、ModeloRATの遠隔操作型マルウェアが展開される。対策としてDNS通信の監視強化、PowerShell実行制限、ユーザー教育が重要である。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[その他]]

- **攻撃手口**
N/A

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
PowerShell実行制限、DNS通信監視強化、ユーザー教育

- **対処方法**
#ClickFix #DNS攻撃 #ModeloRAT
