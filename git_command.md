#	学习git常见命令

添加一个目录：  

	mkdir <dir目录名称>

移动到其他位置：  
 
	cd <路径>

显示当前目录：

	pwd

在当前目录下，初始化git管理的仓库

	git init

将文件添加到暂存区

	git add <file文件名>

将暂存区的所有文件提交到仓库

	git commit -m '输入你本次提交的说明'

查看仓库当前状态

	git status

查看文件不同即文件修改内容

	git diff <file文件>

显示从近到远的提交日志

	git log
	git log --pretty=oneline

回退到上个版本

	git reset --hard HEAD^
	//上个版本HEAD^，上上个版本HEAD^^,n个版本HEAD~n

回退到未来（时间轴以后）的版本

	git reset --hard <commit id>	//commit id前几位就行

记录你的每一次命令

	git refolg





