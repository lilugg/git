# git
git use
(建议)本地工程名和远程仓库名一致

git clone https://github.com/lilugg/git.git

git config --global user.name ""  //用户名
git config --global user.email "" //邮箱

1. git init  
2. git add .
3. git commit -m "初次上传"
4. git push -u origin master(-u 强制上传)


//如果push报错，一般都是本地工程代码没有可提交的， 或者 本地工程不包含远程仓库中某些文件（需要先拉取一次）

git remote add origin https://github.com/lilugg/git.git 	//记录远程仓库
git pull --rebase origin master		//拉取远程仓库到本地
git push origin master		//上传代码到远程仓库

git branch  分支名  创建分支
git checkout 分支名 切换分支
