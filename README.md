test git haha 
小结
要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；
关联后，使用命令  git push -u origin master 第一次推送master分支所有内容。
此后，每次本地提交后，只要想推送到远程库就可以用命令  git push origin master推送最新修改。
pull是从远程库拉取代码到工作区
fetch/clone是从远程库拉取代码到本地库
push是把本地库代码推送到远程库
add是把工作区的修改文件添加到暂存区
commit是把暂存区的修改文件提交到本地库
checkout是把本地库的代码拉取到工作区

git checkout -b dev  新建分支dev并切换到这个分支
相当于下面2条命令
git branch dev
git checkout dev

git branch列出所有分支， 当前分支前面会标一个*号

git merge dev 合并分支dev到当前分支
git branch -d dev 删除dev分支

冲突问题

