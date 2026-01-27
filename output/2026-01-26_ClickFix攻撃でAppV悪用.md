- **収集元サイト**
Bleepingcomputer

- **掲載日**
2026-01-26

- **タイトル**
ClickFix攻撃でAppV悪用

- **概要**
新たなClickFix攻撃はWindowsのAppVスクリプトを悪用しマルウェアを配布する手法である。この攻撃は偽のCAPTCHA検証を用いユーザーにPowerShellコマンドの実行を促す。スクリプトは正規のMicrosoftコンポーネントを利用し悪意ある動作を隠蔽する。ペイロードはステガノグラフィーで隠されPNG画像から復号される。最終的にAmatera情報窃取マルウェアがメモリ上で実行される。感染後はハードコードされたIPと通信し追加ペイロードを受信する。

- **URL**
https://www.bleepingcomputer.com/news/security/new-clickfix-attacks-abuse-windows-app-v-scripts-to-push-malware/

- **備考**
新たなClickFix攻撃は偽CAPTCHAとAppVスクリプト悪用でAmateraマルウェアを配布する。感染はユーザーの手動実行を条件とし解析環境では動作停止する。ペイロードはステガノグラフィーで隠蔽されメモリ上で復号実行される。対策はWindows Runダイアログの制限、AppVコンポーネント削除、PowerShellログ有効化、通信監視が有効である。攻撃は高度化傾向にあり注意が必要である。

- **分類**
[[他組織インシデント]]

- **組織名**
N/A

- **業種**
[[脅威トレンド]]

- **攻撃手口**
[[マルウェア]]

- **攻撃影響**
N/A

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
Windows Run制限、AppV削除、PowerShellログ有効化、通信監視

- **ハッシュタグ**
#ClickFix #Amatera #マルウェア
