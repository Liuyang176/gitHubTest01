### 常用命令:



查看文件信息:cat 文件名

查看当前目录下文件夹中的文件隐藏的不能查看:ls  (  ls -l : A可以查看隐藏文件)

编辑/修改/新增文件:vim 进入文件中 按'a'进入到编写 更改完后按'esc'退出编辑 ':wq' 保存并强制退出

删除文件:rm 文件名;

常看当前状态:git  status

将文件添加到临时空间:git add 文件

提交文件到本地库:  git commit  -m   "提交时的备注信息"   需要提交的文件

查看当前库中提交的历史记录:  git reflog  

返回到指定版本:git reset -- hard 需要返回指定版本处的版本号

git diff 文件名:比较文件差异

​	如果diff在工作区中做比较其实就是和自己比较,没有 差异

​	git diff head [要和那个版本里的文件对比] 要对比的文件  ,这时将修改的文件同本地库中的文件作对比



### 分支管理

创建分支的时候,时复制了一个master东西,到分支的,所以分支是在master上开发

创建分支:  git branch [分支名称] 

查看分支:  git branch -v 

切换分支:  git checkout [分支名]

合并分支:第一步切换到目标分支

​		第二部再目标分支上执行  git merge [需要被合并的分支名]





### 关联远程库

在本地关联远程库: origin 别名 后边是远程库地址

git remote add origin https://github.com/Liuyang176/gitHubTest01.git





将本地库推送到远程库:

 git push [推送]  github01[远程仓库地址别名] master [需要推送的分支名]





