# Push-file-to-remote-repository
如何将本地文件上传到github的远程仓库

> 本方法适用于已配置好git（创建ssh完成）的用户使用终端进行操作
* ssh创建完成后还需要设置本地git个人信息：
```
git config --global user.name "your real name"
git config --global user.email "xxx@gmail.com"
```
## 下面正式开始
1. 从远程克隆
   先把远程的库克隆到本地一个没有.git文件的文件夹下
