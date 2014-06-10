* 基本的なコマンド
    * masterブランチから開発用の新しいブランチを作る/git checkout -b new_branch_name
    * 今のローカルの状態を見たい時/git status
    * ローカルで書いた差分を見る/git diff
    * ローカルの差分をcommitするための準備/git add
    * git add を取り消したいときには/git reset
    * ブランチに差分をcommitする/git commit
    * リモートにブランチを渡すための/git push

* 困った時
    * リモートのデータをダウンロードしてきたい/git fetch
    * masterブランチが古くなったので新しい部分を取り込みたい/git merge origin/master
    * git fetch と git merge を一緒にやってしまいたい/git pull
    * これまでどんなコミットをしたか確認したい/git log
    * 前のコミット内容を見たい/git show
    * 直前の動作をやり直したい/git reflog, git reset
    * 前のコミットを取り消したい/ git revert コミット番号
    * 前のコミットと一緒にコミットしたい差分があった/ git commit --amend
    * git push origin master って打つのが面倒/git push -u origin masterからのgit push
    * ローカルのブランチを消したい/git branch -D ブランチ名
    * リモートのブランチを消したい/git push origin :ブランチ名
    * もっと困った/http://www.backlog.jp/git-guide/reference/

* チーム内のルール
    * コミットメッセージはadd/change/removeから始める
