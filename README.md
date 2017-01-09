curl -u 'username' https://api.github.com/user/repos -d '{"name":"RepoName"}'
git commit -m "git process"
git remote add origin git@github.com:username/RepoName.git
(RSA方法，不用每次密码)
git remote add origin https://github.com/zhangzj03/remote-create-hello-world.git
(用每次密码)
(git remote set-url origin xxxx)
(git remote rm origin  ;git remote add origin xxxx)

git remote
git remote -u
git push -u origin master

git add [filename or folder name]
 	


git push origin master



#vimdiff
vimdiffget vimdiffput

zo zc
]c [c

#wget 


#tar.gz
tar -xzvf  XXX.tar.gz





git 查看远程分支、本地分支、创建分支、把分支推到远程repository、删除本地分支 
http://blog.csdn.net/arkblue/article/details/9568249/
创建本地分支
git branch test
切换到本地分支
git checkout test
查看本地分支
git branch
把本地把分支推到远程分支 
git push origin test
查看本地分支和远程分支
git branch -a







命令行中新建Github远程仓库
http://www.tuicool.com/articles/biQBRfR
curl -u 'username' https://api.github.com/user/repos -d '{"name":"RepoName"}'
其中，username是你的用户名，RepoName是你想命名的仓库名。这条命令执行后输入密码就创建成功了，会有仓库相关信息的回显。

接着，就可以添加远程仓库并Push:

Vim

git remote add origin git@github.com:username/RepoName.git
（每次密码）
git push origin master













1.5.2 Git之使用GitHub搭建远程仓库
http://www.runoob.com/w3cnote/android-tutorial-git-repo-create.html

http://git.oschina.net/


