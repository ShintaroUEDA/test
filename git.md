# Git(Github) #

## リモートリポジトリ ##
### GitHubでリポジトリを作成する ###
- RepositoryでCreate New Repositoryする。

## ローカルリポジトリ (Windows) ##
- ### ローカルリポジトリからプッシュ ###
1. リポジトリのフォルダを作成
2. Gitリポジトリとして初期化　　
```
    git init
```
3. ファイルをローカルリポジトリに追加
```
    git add **filename**
```
4. インデックスに追加されたファイルをコミット    
```
    git commit -m "add new file"
    *-m ...message
```
5. 確認
```
    git status
```
6. リモートリポジトリの情報を追加
```
    git remote add origin **url**
    *url...ex)**https://github.com/repositoryname.git**
```
7. リモートリポジトリに反映
```
    git push origin master
```
### リモートリポジトリの確認 ###
```
    git remote -v
        origin  https://github.com/uedshin/knowledge.git (fetch)
        origin  https://github.com/uedshin/knowledge.git (push)
```
