# 相关技术

## Ubuntu下python解释器的安装
[python安装教程]（http://jingyan.baidu.com/article/eae07827f7f2d01fec5485f7.html）

## Ubuntu下github使用方法

## Python在机器学习中的应用

## TensorFlow使用方法

## Git常用命令
git init # 初始化本地Git版本库
git add # 暂存文件，如果使用.表示当前目录及其子目录
git commit -m “first commit” # 提交，-m选项后跟内容为提交所用的注释
git remote -v # 查看当前项目远程连接的是哪个版本库地址
git push origin master # 将本地项目提交到远程版本库
git fetch origin # 取得远程更新（到origin/master），但还没有合并
git merge origin/master # 把更新的内容（origin/master）合并到本地分支（master）
git pull origin master # 相当于fetch和merge的合并，但分步操作更保险
git branch -r #查看分支
git checkout origin/master(gh-pages) #切换分支
git push origin :branch_you_want_to_delete #删除远程分支（注意空格，把一个空的branch赋值给已有的branch，这样就删除了）
