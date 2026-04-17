- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-04-16

- **タイトル**
New Microsoft Defender RedSun PoC

- **概要**
研究者が新たなMicrosoft Defenderのゼロデイ脆弱性「RedSun」のPoCを公開した。この脆弱性はWindows 10、11およびWindows Serverの最新パッチ適用環境でSYSTEM権限を取得可能とするローカル権限昇格の欠陥である。攻撃はWindows Defenderのファイル上書き動作を悪用し、システムファイルを書き換えて管理者権限を獲得する。検証済みであり、複数の環境で動作確認されている。研究者はMicrosoftの対応に不満を示している。

- **URL**
https://www.bleepingcomputer.com/news/microsoft/new-microsoft-defender-redsun-zero-day-poc-grants-system-privileges/

- **備考**
この脆弱性は[[RedSun]]と呼ばれ、Windows DefenderのクラウドファイルAPIの動作を悪用する。攻撃者はファイルの再書き込み機能を利用し、システムファイルを置換してSYSTEM権限を取得する。将来的に類似の攻撃が増加する可能性が高く、検知回避技術も確認されている。対策としては最新パッチ適用の徹底と異常なファイル操作の監視が推奨される。攻撃は高度であるため専門的な対応が必要である。

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
最新パッチ適用、ファイル操作監視、不審プロセス検知

- **対処方法**
#RedSun #MicrosoftDefender #ゼロデイ
