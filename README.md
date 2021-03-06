# 基础知识

## 机器学习相关资料
首先列举两个搜集机器学习学习资料的开源库  
[awesome-machine-learning](https://github.com/Zhangzhk0819/awesome-machine-learning.git)  
[Qix](https://github.com/Zhangzhk0819/Qix.git)

## 经典Python机器学习库
### tensorflow
tensorflow主要擅长基于神经网络的机器学习方法，包括目前比较火的深度学习。  
这是一个比较完整的[中文教程](https://github.com/Zhangzhk0819/tensorflow-zh.git)。

### scikit
scikit擅长的领域比较多，包括各种分类聚类算法，可以和tensorflow结合起来使用。

## 分布式计算框架
hadoop  
spark

## 数据可视化

## 其他相关技术
### Ubuntu下python解释器的安装
[python安装教程](http://jingyan.baidu.com/article/eae07827f7f2d01fec5485f7.html)

### Git基本操作
更多内容参考[https://git-scm.com/doc](https://git-scm.com/doc)
### Git常用命令
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
  
git remote -v #查看远程URL版本  
git remote set-url origin git@github.com:USERNAME/OTHERREPOSITORY.git #把URL地址从HTTPS切换到SSH  
git remote set-url origin https://github.com/USERNAME/OTHERREPOSITORY.git #把URL地址从SSH切换到HTTPS  
  
### Git基本操作
[远程操作](http://www.ruanyifeng.com/blog/2014/06/git_remote.html)  
[分支的新建与合并](https://git-scm.com/book/zh/v1/Git-%E5%88%86%E6%94%AF-%E5%88%86%E6%94%AF%E7%9A%84%E6%96%B0%E5%BB%BA%E4%B8%8E%E5%90%88%E5%B9%B6)
