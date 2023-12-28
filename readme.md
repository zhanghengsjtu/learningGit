# 本地仓库
1. git init
2. git commit .
3. git commit -A src/*
4. git commit -m "some useful message"

# 基本命令
1. git status
2. git log
3. git reset --hard uuid

# 分支管理
1. git branch feature1
2. git branch -d feature
3. git switch master
4. git merge feature1

# 远程仓库
1. git remote add origin github-url
2. git push -u origin master
3. git push --set-upstream origin master
4. git fetch origin
5. git merge origin/master
6. git pull 

# 冲突解决
1. git merge feature1
2. 手动修改文件
3. git commit
4. git push