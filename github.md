#### ローカルリポジトリを新規作成
git init  

#### gitステイタスを確認
git status  
#### インデックスに追加
git add _file_name_  or  git add .  

#### 変更を反映
git commit -a //変更のあったファイルすべて  
git commit --amend //直前のコミットを取り消す  
git commit -v //変更点を表示してコミット  
git commit -m _commit_name_  //コミットメッセージを指定  

#### originという名前のリモートリポジトリを作成
git remote add origin _URL_  

#### originリモートリポジトリのmasterブランチをプルする(pushする前にやっておくこと）
git pull origin master  

#### originリモートリポジトリのmasterブランチにプッシュする
git push origin master  

