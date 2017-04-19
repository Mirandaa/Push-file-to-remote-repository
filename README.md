# Push-file-to-remote-repository
如何将本地文件上传到github的远程仓库

> 本方法适用于已配置好git（创建ssh完成）的用户使用终端进行操作
* ssh创建完成后还需要设置本地git个人信息：
```
git config --global user.name "your real name"
git config --global user.email "xxx@gmail.com"
```

## 下面正式开始

> 1. 从远程克隆把远程的库克隆到本地一个没有.git文件的文件夹下
![git1](https://github.com/Mirandaa/img-folder/blob/master/images/git1.png)

> 2. 进入到刚才那个库里<br>
 * 然后用`touch`创建文件（本地也可以直接放在文件夹里，这里新建文件只做测试用）
 * `vi`编辑一下（不知道空文件会怎么样？）
 * `git add`将告诉Git，把文件添加到缓存区（index）
 * `git commit -m "xxxx"`告诉Git，把文件提交到最后一次指向的结果（head），而`-m`后面输入的是本次提交的说明
 * `git pull`一下，更新我的本地仓库，这样就可以将本地仓库修改过的文件上传到远程仓库啦
 * 最后`git push origin master`，如果如图显示的话就成功了~
![git2](https://github.com/Mirandaa/img-folder/blob/master/images/git2.png)
