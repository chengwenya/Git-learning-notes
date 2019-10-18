一、介绍与安装
	安装包已经放在tool目录下，包含了gui的汉化工具。

二、工作流
	工作区      暂存区    版本库
	git init   git add   git commit

三、远程仓库
	①git remote add 把本地仓库关联到远程仓库，例如：git remote add origin https://github.com/chengwenya/test.git
	②git push 将本地代码推到远程仓库
	③git pull 将远程仓库拉到本地仓库
	④git clone 将远程仓库克隆到本地

四、分支管理
	①git branch 查看分支
	②git branch name 创建分支
	③git checkout name 切换分支
	④git merge name 合并分支（如果当前分支不在master分支上，需要执行git checkout命令切换到主分支上，在执行此命令）
	⑤git branch -d name 删除分支

五、标签管理
	①git tag 查看标签
	②git tag name 创建标签
	③git tag -a name -m "comment" 指定提交信息
	④git tag -d name 删除标签
	⑤git push origin name 发布标签
