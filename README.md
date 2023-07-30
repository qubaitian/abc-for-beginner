# abc-for-beginner
## git
管理文件使用git,以下是几个常用命令
```
从远程clone仓库到本地
git clone
初始化当前文件夹
git init
把文件加入到仓库中
git add
提交文件修改内容
git commit -am 'some comment'
推送到远程仓库
git push
从远程仓库拉取内容
git pull
```
git可以使用http和ssh两种方式,ssh方式,其实就是把github或者远程仓库当成ssh的服务器
## 文件/file
命令的可读性,复用性很低,就是读起来不直观,写错了也不知道咋回事,然后想要改改继续用也很不方便,所以需要把让服务器做的事(程序),处理的数据记录(数据)在文件里,如果希望使用python格式,记录这些东西,那就写XXX.py,如果希望写html,那就写XXX.html,`.py` `.html` 这种叫做文件的扩展名
## 网络服务
所谓的互联网工作,就是提供网络服务,一个最简单情况是,一个运行在服务器上面的程序,web程序加上server服务器,就是网络服务器了,可以提供网络服务的程序有很多,比如nginx,tomcat,各种框架也会内置一些网络服务
## 服务
本质上,允许其他人的登陆到自己的服务器,这其实就是一个服务,可以让其他服务器连接到这台服务器,而别人想要使用这个服务就需要访问地址和端口,也就是`ssh -p 22 qubaitian@192.168.31.8`,再比如网络服务,http的请求默认是80,http的demo项目一般默认是8080,假如本地启动一个demo项目的话一般就会再192.168.31.8:8080,而https默认的是443
## 地址端口/url/address&port
服务器各种服务暴露的地址,一般情况下使用地址加端口的形式,比如在家,用同一个路由器的情况,可以ssh链接,ssh默认的端口往往是22,不写就默认
```
连接我的电脑
ssh qubaitian@192.168.31.8
连接你自己的电脑
ssh xiaowensha@127.0.0.1
```
## ssh
各种命令里面最常用的就是ssh,可以登陆其他服务器,可以使用密码和公钥私钥方式,简单来说,公钥就是锁,私钥就是钥匙,设置了公钥,其实就是往门上按一把锁,再通过私钥就可以开门了
##  命令行/command line
在没有图形界面之前,和服务器交互的方式就是命令行,简单理解就是小黑框,输入一些命令,让服务器做一些操作,比如一些服务的开启结束,查看日志,都需要通过命令操作
## 操作系统/operating system
上面提到的windows,mac,linux,就是操作系统,一般情况下,个人电脑就是windows和mac,一般生产环境的服务器用linux操作系统
## 服务器/server
服务器是最基本的完整的工作单位,各种软件运行在上面,它可以是一个windows笔记本,可以是一个mac笔记本,也可以是linux虚拟机
## 说明
[Custom foo description](#)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTMzODc1MjU5MywtMTc5ODc5MjkwLC0xNT
M4NDY5NTc4LDE2ODU0MjA1MzRdfQ==
-->