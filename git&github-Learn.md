# Git and Github学习笔记

Git是一个运行在电脑上的版本控制软件，Github是基于Git打造的网站

## Git
### 官方网站
**Git官网：** https://git-scm.com
### 三个概念
Commit

Repository

Branch

### 相关操作
**Git操作流程**
#### 提交操作

工作区-->暂存区-->仓库
1. `git init`初始化仓库
2. `git add -A`全部提交
3. `git commit -m "提交信息"`进入仓库
#### 维护项目
1. 从工作区打回
`git checkout "文件名"`
2. 提交后撤回
`git reset HEAD^`
#### 分支
1. 以当前分支为基础新建分支
`git checkout -b branchname`
2. 列举所有分支
`git branch`
3. 单纯地切换到某个分支
`git checkout <branchname>`
4. 删掉特定的分支
`git branch -D <branchname>`
5. 合并分支
`git merge <branchname>`
6. 放弃合并
`git merge --abort`

也可以不输入命令，通过vscode自带功能完成操作