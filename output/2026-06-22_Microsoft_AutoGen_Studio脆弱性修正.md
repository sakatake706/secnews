- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-06-22

- **タイトル**
Microsoft AutoGen Studio脆弱性修正

- **概要**
MicrosoftのAutoGen Studioに存在したAutoJackと呼ばれる脆弱性は、ローカルホストからの信頼された接続を悪用し、認証チェックの欠如とbase64エンコードされたパラメータの処理により、攻撃者が任意のコマンドを実行可能とした。影響は開発者向けの限定的な期間に限られ、公開パッケージには含まれていない。

- **URL**
https://www.bleepingcomputer.com/news/security/microsoft-fixes-autogen-studio-flaw-that-enabled-code-execution/

- **備考**
AutoJack脆弱性は開発環境における権限昇格を狙い、ローカルの信頼接続を悪用する点が特徴である。攻撃はJavaScript経由でWebSocket接続を開き、任意のPowerShellやBashコマンドを実行可能とする。対策としては開発環境の隔離、低権限アカウントでの実行、認証強化が推奨される。将来的な類似攻撃の防止に重要な知見を提供する。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[産業分類]]

- **攻撃手口**
[[標的型攻撃]]

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
開発環境隔離、低権限実行、認証強化

- **ハッシュタグ**
#AutoJack #AutoGenStudio #脆弱性
