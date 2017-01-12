# git的入门教程
>复杂内容请看[教程](http://www.runoob.com/git/git-tutorial.html)

---
其实git的操作也不是很复杂，当然也不是那么简单，这里呢，我就教一些很容易很常见的操作就OK了

本教程适合初学者，并且配合GitHub，可以快速上手

1. 建立git
  1. mkdir 文件夹名字
  2. git init
  3. 往文件夹内添加内容
  4. git add filename
  5. git commit -m “注释”
2. 修改内容
  1. 使用git checkout --filename 可以将暂存区和工作区内容替换。就是将暂存区的东西替换给工作区
  2. git reset --hard id 可以切换 commit的不同版本
  3. git reset HEAD filename 可以将add后的东西并且还没有commit的东西取消掉。
  4. 如果已经commit想要更改，那么就使用reset 来进行更改
  5. 如果已经传送给github 那么请在github中的设置中，页面最低端 输入filename进行删除
3. 增加branch
  1. 增加branch git branch branchName
  2. 更改branch git checkout branchName
  3. 删除branch git branch -d branchName
  4. 合并 （切换到主干branch）在主干中使用 git merge 枝干的branch
4. 连接github
  1. 使用git remote add origin git@github.com:NAME/filename.git
  2. git push origin master
5. 更多教程后续更改
