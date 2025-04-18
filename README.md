# GitHubの使い方
鳥科電装26代におけるブラウザ版のGitHubで開発を進める方針についてまとめる．

## 方針
- 必要要件は，誰による, どんな編集かが明確にわかること. 
- ローカルファイルの同期は必ずしも必須ではない. 
- Gitの構造を理解しきれていない人がいる中でGitの利用を強制するのは得策ではない. 
- 「ファイルの変更履歴を残せるクラウドストレージ」としての利用ならブラウザ版で十分と判断した. 

## 練習
|1|右上の緑の「\<\> Code」をクリックする．|  
|---|:---|
||<img src="images/code_button.png">|

|2|「Download ZIP」をクリックする．|
|---|:---|
||<img src="images/download_zip_button.png">|

|3|任意のフォルダーで展開する．|
|---|:---|
||作業をする展開先のフォルダーをあらかじめ決めておくと良いでしょう．<br><br><img src="images/unzipping.png" width="500px"><br><br><img src="images/unzipped.png" width="500px">|

|4|作業をする．|
|---|:---|
||すべてのファイルに何かしらの文字を追記して保存しましょう．ここでは「Modified!」と追記しました．<br><br><img src="images/modifing_txt_file.png" width="400px">|

|5|GitHubのリポジトリにアップロードする．|
|---|:---|
||右上の「Upload files」からアップロードできます．ただし，アップロードする場所を状況に応じて適切に選択してください．<br><br>**a. あるファイルを1つだけ編集した場合**<br>画像を参考に「a.txt」をアップロードしましょう．<br><br><img src="images/uploading_one_file.png" width="500px"><img src="images/adding_one_file.png" width="350px"><br><br>**b. 特定のフォルダー内にある1つのファイルを編集した場合**<br>画像を参考に，もともと「b.txt」があった場所（dir1）に移動してから **a.** と同様に「b.txt」をアップロードしましょう．<br><br><img src="images/cd_to_dir1.png" width="500px"><br><br><img src="images/uploading_one_file_in_dir1.png" width="500px"><br><br>**c. 特定のフォルダー内にある複数のファイルを編集した場合**<br>画像を参考に「c.txt」「d.txt」が入っているフォルダー（dir2）ごとドラッグ＆ドロップして，アップロードしましょう．**b.** と同様に場所を移動してから，複数選択してドラッグ＆ドロップすることもできます．<br><br><img src="images/adding_folder.png" width="500px">|

|6|新しいブランチにコミットする．|
|---|:---|
||ラジオボタンで下のオプション「Create a **new branch** ...」を選択します．ブランチ名は自動入力されたものをそのまま使用するようにしましょう．（{UserName}-patch-1など）<br><br><img src="images/create_a_new_branch.png" width="500px">|

|7|Pull Requestを作成する．|
|---|:---|
||自身の変更に対する承認を要求できます．特に何も手を加えずに続行しましょう．<br><br><img src="images/creating_pull_request.png" width="500px"><br><br><img src="images/created_pull_request.png" width="500px">|

### 以降はMainブランチに変更を与える操作です．<br>基本的にはそのリポジトリを管理するユーザー自身が操作してください．

|8|Pull RequestをMergeする．|
|---|:---|
||変更を承認する場合は，Pull RequestをMergeして変更を適用しましょう．「No conflicts」とある場合は問題なくMergeできます．<br><br><img src="images/merging_pull_request.png" width="500px"><br><br><img src="images/merged_pull_request.png" width="500px">|

|9|不要なブランチを消す．|
|---|:---|
||Mergeが完了し，不要になったブランチは消すことができます．「Delete branch」をクリックしましょう．「Revert」や「Restore branch」で復元することができます．<br><br><img src="images/closed_pull_request.png" width="500px">|

**以上です！お疲れさまでした！**
