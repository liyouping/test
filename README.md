test git haha 
小结
要关联一个远程库，使用命令git remote add origin git@server-name:path/repo-name.git；
关联后，使用命令  git push -u origin master 第一次推送master分支所有内容。
此后，每次本地提交后，只要想推送到远程库就可以用命令  git push origin master推送最新修改。
