- **収集元サイト**
Bleepingcomputer

- **掲載日**
2025-09-11

- **タイトル**
VMScape攻撃がCPUの隔離破壊

- **概要**
新たなVMScape攻撃はAMDおよびIntelのCPUにおけるゲストとホスト間の隔離を破壊する。Spectre類似の手法を用い、仮想マシンからハイパーバイザーの暗号鍵を漏洩させることが可能である。攻撃は未改変のQEMU上で動作し、既存の緩和策を回避する。ETH Zurichの研究者が発見し、Zen1からZen5のAMDプロセッサとIntelのCoffee Lake世代が影響を受ける。攻撃は高度な専門知識と時間を要し、広範なユーザーへの即時脅威とはならない。

- **URL**
https://www.bleepingcomputer.com/news/security/new-vmscape-attack-breaks-guest-host-isolation-on-amd-intel-cpus/

- **備考**
VMScape攻撃は仮想環境の隔離を破壊し、暗号鍵などの機密情報を漏洩させる。攻撃者はSpectre-BTIを利用し、QEMUの分岐予測を誤誘導することで情報を取得する。対策としてLinuxカーネルのパッチが提供され、IBPBの導入により性能低下を抑えつつ緩和が可能である。将来的には類似攻撃の拡大が懸念され、継続的な監視と更新が必要である。攻撃は高度な技術を要するため限定的な影響に留まる見込みである。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[脅威トレンド]]

- **攻撃手口**
[[標的型攻撃]]

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
パッチ適用、IBPB導入、監視強化

- **ハッシュタグ**
#VMScape #Spectre #仮想化
