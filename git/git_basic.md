
- # Gitとは
- 分散型バージョン管理ツール
- ファイルの状態を好きな時に変更履歴として保存可能
- つまり、一度編集したファイルを過去に戻したり、編集箇所の差分を表示できる

## $ git remote add [shortname] [url]
慣習として<shortname>がoriginですが、<url>の別名で付けてるだけなのでなんでもいいみたい
originという名前に紐づけられている<url>は
## $ git remote get-url [shortname]

# 学んだコマンド
```
mkdir repos
cd repos
git config --global user.name "{account name}"
git config --global user.email {mailaddress}
git clone {url}
cd test-git
echo "# test1" >> README.md
git status
git add README.md
git status
git commit -m "first commit"
git status
git log
git push origin master
```
