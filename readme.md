# readme

+ 项目说明文档
  ## git init
    1.初始化版本库
    2.生成隐藏文件
## git add
    把当前目录下文件提到到暂存区
    git add . 所有文件提交到暂存区
## git status
    查看当前目录状态
## 本地仓库的三个组成部分
1. 工作区（实际持有文件）
2. 暂存区
3. 本地仓库
## git log
查看日志
## git reflog
显示部分信息
## git diff 文件名
查看文档修改的信息

## git reset --hard 版本号
## git reset --hard^回退到上一个版本

## 远程仓库  git remote add origin 仓库地址
 把本地仓库与远程仓库关联
## git remote -v
查看本地仓库关联的远程仓库地址
可以关联多个 ，origin是别称
## git push -u origin master
1. git push 本地仓库提交到远程仓库
2. -u origin master 设置默认远程仓库和分支
3. upstream 执行完这个命令之后，以后可以直接 git push 提交到远程仓库的master分支