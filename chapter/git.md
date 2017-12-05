
# 我的笔记

###新建分支

  每次开发新功能，都应该新建一个单独的分支

  ####获取主干最新代码

      git checkout master

      git pull

  ####新建一个开发分支myfeature

      git checkout -b myfeature

###提交分支commit

  分支修改后，就可以提交commit了。

    git add .

    git status 用来查看发生变动的文件

    git commit -am '' 对修改的文件进行标记

    git push origin + 远程仓库 

  提交到远程仓库以后，就可以发出 Pull Request 到master分支，然后请求别人进行代码review，确认可以合并到master。


 
