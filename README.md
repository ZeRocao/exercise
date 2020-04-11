
# a git note   
### Basic Syntax   
* git init                                              
创建本地仓库   
*************************************
* git add + filename    
把本地仓库中的file提交到暂存区   
·  git add -A  提交所有变化   
·  git add -u  提交被修改(modified)和被删除(deleted)文件，不包括新文件(new)   
·  git add .  提交新文件(new)和被修改(modified)文件，不包括被删除(deleted)文件   
*************************************
* git commit + filename   
把暂存区的file提交到版本库   
*************************************
* git push        
把版本库中的文件提交到远程仓库               
例如 git push origin master：refs/for/master ，即是将本地的master分   
支推送到远程主机origin上的对应master分支， origin 是远程主机名， 第   
一个master是本地分支名，第二个master是远程分支名。   
*************************************
* git pull origin master   
把远程仓库master与本地当前分支合并，即拉取最新资源   
*************************************
* git remote add origin http://xxxx     
与远程仓库连接   
************************************8
* git branch   
列出当前分支   
*************************************
* git clone "address" "name"   
克隆远程仓库到本地当前位置    
*************************************
* git checkout "branchname"    
切换分支     git checkout -b "branchname" 创建并切换   
************************************
* git status   
查看文件的状态   
*************************************
* git log   
查看历史   