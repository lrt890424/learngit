# learngit
## 全局配置
**git config --global user.name** "Your Name"  
**git config --global user.email** "email@example.com"  
## 提交文件
**git add** file，注意，可反复多次使用，添加多个文件  
**git commit -m** "message"，完成。
## 查看状态
**git status** 查看状态  
**git diff** 查看更改  
**git log** 查看提交历史  
**git reflog** 查看命令历史
## 版本回退
**git reset --hard** commit_id 回退某个版本  
**git reset --hard HEAD^** 回退上一个版本
## 回退修改
**git checkout --** file  
场景1：当你改乱了工作区某个文件的内容，想直接丢弃工作区的修改时，用命令。

**git reset HEAD** file  
场景2：当你不但改乱了工作区某个文件的内容，还添加到了暂存区时，想丢弃修改，分两步，第一步用命令回到了场景1，第二步按场景1操作
## 删除文件
**git rm** file 用于删除一个文件
## 关联远程仓库
**git remote add origin** git@server-name:path/repo-name.git  
**git push -u origin master**  第一次推送master分支的所有内容
## 从远程仓库克隆
**git clone** *git@server-name:path/repo-name.git*
## 分支
**git branch**  查看分支  
**git branch** name  创建分支  
**git checkout** name 切换分支  
**git checkout -b** name 创建+切换分支  
**git merge** name 合并某分支到当前分支  
**git branch -d** name 删除分支
 



