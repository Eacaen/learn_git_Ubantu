在此附上git常用命令以供使用：

git clone <address>：复制代码库到本地；

git add <file> ...：添加文件到代码库中；

git rm <file> ...：删除代码库的文件；

git commit -m <message>：提交更改，在修改了文件以后，使用这个命令提交修改。

git diff 查看当前工作树与暂存区的区别 
	<+>表示新添加的行;<->表示被删除的行

git diff HEAD 查看工作树与最新提交的区别

git log：查看提交记录（即历史的 commit 记录）

git pull：从远程同步代码库到本地。

git push：推送代码到远程代码库。

git branch：查看当前分支。带*是当前分支。

git branch <branch-name>：新建一个分支。

git branch -d <branch-name>：删除一个分支。

git checkout <branch-name>：切换到指定分支。

git checkout -b <branch-name>：创建,切换到指定分支。

git checkout -切换至上一分支

git status：当前修改的状态，是否修改了还没提交，或者那些文件未使用。

git reset <log>：恢复到历史版本。
