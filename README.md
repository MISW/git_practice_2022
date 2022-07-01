# 説明
- 2022年度、git練習用のレポジトリ 
- 自分のハンドルネームでブランチを切った上で、testディレクトリ配下にファイルを作成し、プルリクエストを出してください！ 

# 準備
- gitのインストール
- GitHubアカウントの作成 

# 流れ
1. このレポジトリをclone
1. cloneしたレポジトリへ移動: ```cd git_practice_2022```
1. ブランチを切る: ```git checkout -b ${ブランチ名を入力}```
1. test/ディレクトリ配下にファイルを作る
1. check status: ```git status``` 
   - untrack filesに作ったファイルが表示されているはず
1. add: ```git add .```
1. check status: ```git status``` 
   - Changes to be commitedに作ったファイルが表示されているはず
1. commit: ```git commit -m "${コミットメッセージを入力}"```
1. check status: ```git status```
   - nothing to commit, working tree cleanと表示されているはず
1. push: ```git push origin ${ブランチ名を入力}```
1. プルリクエストをmainブランチに対して出す 
1. マージされるのを待つ
