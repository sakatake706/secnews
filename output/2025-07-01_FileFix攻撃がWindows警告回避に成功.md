- **収集元サイト**
Bleepingcomputer

- **掲載日**
2025-07-01

- **タイトル**
FileFix攻撃がWindows警告回避に成功

- **概要**
新たなFileFix攻撃はWindowsのMark of the Web保護を回避し、保存されたHTMLファイルの扱いを悪用して悪意あるJScriptを実行する手法である。この攻撃はユーザーを騙してHTMLページを保存し拡張子を変更させる社会工学的手法を用い、mshta.exeを通じてスクリプトを警告なしに実行させる。攻撃の核心はユーザーの操作誘導であり、対策としてmshta.exeの無効化やファイル拡張子の表示設定が有効である。

- **URL**
https://www.bleepingcomputer.com/news/security/new-filefix-attack-runs-jscript-while-bypassing-windows-motw-alerts/

- **備考**
新たなFileFix攻撃はMark of the Web保護を回避し、保存されたHTMLファイルの扱いを悪用して悪意あるJScriptを実行する手法である。攻撃者はユーザーを騙してHTMLページを保存し拡張子を変更させる社会工学的手法を用い、mshta.exeを通じてスクリプトを警告なしに実行させる。攻撃の核心はユーザーの操作誘導であり、対策としてmshta.exeの無効化やファイル拡張子の表示設定が有効である。

- **分類**
[[脅威分析]]はこの攻撃がユーザーの操作誘導を巧みに利用し、Windowsの正規プロセスを悪用する点にある。攻撃者は社会工学的手法で被害者に悪意あるファイル保存を促し、mshta.exeを介してスクリプトを実行させる。推奨対策はmshta.exeの無効化、ファイル拡張子の表示設定強化、HTML添付ファイルのブロックである。将来的に類似の手法が増加し被害拡大の可能性が高い。

- **組織名**
[[注意喚起]]

- **業種**
N/A

- **攻撃手口**
N/A

- **攻撃影響**
[[標的型攻撃]]

- **脅威アクター**
N/A

- **原因**
N/A

- **対処方法**
mshta.exe無効化、ファイル拡張子表示設定強化、HTML添付ファイルブロック

- **ハッシュタグ**
#FileFix #WindowsSecurity #注意喚起
