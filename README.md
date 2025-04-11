# GitHubの使い方
鳥科電装26代におけるブラウザ版のGitHubで開発を進める方針についてまとめる．

## 方針
- 必要要件は，誰による, どんな編集かが明確にわかること. 
- ローカルファイルの同期は必ずしも必須ではない. 
- Gitの構造を理解しきれていない人がいる中でGitの利用を強制するのは得策ではない. 
- 「ファイルの変更履歴を残せるクラウドストレージ」としての利用ならブラウザ版で十分と判断した. 

## 手順
|1|右上の緑の「\<\> Code」をクリックする．|  
|---|:---|
||<img src="images/code_button.png">|

|2|「Download ZIP」をクリックする．|
|---|:---|
||<img src="images/download_zip_button.png">|

|3|任意のフォルダーで展開する．|
|---|:---|
||作業をする展開先のフォルダーをあらかじめ決めておくと良いでしょう．<br><img src="images/unzipping.png" width="500px"><br><img src="images/unzipped.png" width="500px">|

|4|作業をする．|
|---|:---|
||すべてのファイルに何かしらの文字を追記しましょう．ここでは「Modified!」と追記しました．<br><img src="images/modifing_txt_file">|

|5|GitHubのリポジトリにアップロードする．|
|---|:---|
||右上の「Upload files」からアップロードできます．ただし，アップロードする場所を状況に応じて適切に選択してください．<br><br>**a. あるファイルを1つだけ編集した場合**<br>画像を参考に「a.txt」をアップロードしましょう．<br><img src="images/uploading_one_file.png" width="500px"><img src="images/adding_one_file.png" width="300px"><br><br>**b.特定のフォルダー内にある1つのファイルを編集した場合**<br>画像を参考に，もともと「b.txt」があった場所（dir1）に移動してから「b.txt」をアップロードしましょう．<br><img src="images/cd_to_dir1.png" width="500px"><br><br><img src="images/uploading_one_file_in_dir1.png" width="500px"><br><br>**c. 特定のフォルダー内にある複数のファイルを編集した場合**<br>画像を参考に「c.txt」「d.txt」が入っているフォルダー（dir2）ごとドラッグ＆ドロップして，アップロードしましょう．**b.** と同様に場所を移動してから，複数選択してドラッグ＆ドロップすることもできます．<br><img src="images/adding_folder.png" width="500px">|

