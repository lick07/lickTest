git init							创建版本库  
git add <file>						把文件添加暂存区  
git commit -m "comment"				把文件提交到当前分支  
git status							查看当前状态  
git diff <file>						查看具体修改内容  
git log								查看修改日志  
git log --pretty=oneline			查看版本号  
git reset --hard HEAD^				回退到上一版本 (回退到上n个版本 HEAD~n)  
git reset --hard 版本号(1094a)		指定回到未来的某一版本(版本号没必要写全)  
git reflog							查看历史命令  
git diff HEAD -- <file>				工作区和版本库的区别  
git checkout -- <file>				撤销文件在工作区的修改  
git reset HEAD <file>				撤销文件在暂存区的修改  
git restore --staged <file>			删除add到暂存区的文件  
git remote add origin https://github.com/lick07/lickTest.git  关联远程库  
git push -u origin master			关联后第一次推送master分支的所有内容  
git push origin master				推送最新修改  
git checkout -b dev					创建并切换分支  ==>git branch dev ==>git checkout dev  
	git switch -c dev				创建并切换分支  
	git switch master				切换分支  
git branch 							查看分支  
git checkout master|dev				切换分支  
git merge dev						合并指定分支到当前分支  
git branch -d dev					删除指定分支  