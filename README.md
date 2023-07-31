# abc-for-beginner
## server
服务器是一个最基本的完整的工作单位,各种服务运行在上面,它可以是一个windows台式机,可以是一个mac笔记本,也可以是linux虚拟机
## service
简单理解服务就是程序,允许其他人的登陆到自己的服务器,这其实就是一个服务,可以让其他服务器连接到这台服务器,而别人想要使用这个服务就需要访问地址和端口,也就是`ssh -p 22 qubaitian@192.168.31.8`,再比如网络服务,http的请求默认是80,http的demo项目一般默认是8080,假如本地启动一个demo项目的话一般就会再192.168.31.8:8080,而https默认的是443
## url/address&port
[mdn关于url的介绍](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/What_is_a_URL)
服务器各种服务暴露的地址,一般情况下使用地址加端口的形式,比如在家,用同一个路由器的情况,可以ssh链接,ssh默认的端口往往是22,不写就默认
|命令|效果|
|--|--|
| ssh qubaitian@192.168.31.8 | 连接我的电脑 |
|ssh xiaowensha@127.0.0.1|连接你自己的电脑|
## operating system
上面提到的windows,mac,linux,就是操作系统,一般情况下,个人电脑就是windows和mac,一般生产环境的服务器用linux操作系统
##  command line
在没有图形界面之前,和服务器交互的方式就是命令行,简单理解就是小黑框,输入一些命令,让服务器做一些操作,比如一些服务的开启结束,查看日志,都需要通过命令操作
## ssh
各种命令里面最常用的就是ssh,可以登陆其他服务器,可以使用密码和公钥私钥方式,简单来说,公钥就是锁,私钥就是钥匙,设置了公钥,其实就是往门上按一把锁,再通过私钥就可以开门了
## web-service
所谓的互联网工作,就是提供网络服务,一个最简单情况是,一个运行在服务器上面的程序,web程序加上server服务器,就是网络服务器了,可以提供网络服务的程序有很多,比如nginx,tomcat,各种框架也可以提供网络服务,前端比如vue和react,后端比如flask,spring
## file
命令的可读性,复用性很低,就是读起来不直观,写错了也不知道咋回事,然后想要改改继续用也很不方便,所以需要把让服务器做的事(程序),处理的数据记录(数据)在文件里,如果希望使用python格式,记录这些东西,那就写XXX.py,如果希望写html,那就写XXX.html,`.py` `.html` 这种叫做文件的扩展名
## git 
管理文件使用git,以下是几个常用命令
| 命令 | 效果 |
|--|--|
| git clone | 从远程clone仓库到本地 |
| git init | 初始化当前文件夹 |
| git add | 把文件加入到仓库中 |
| git commit -am 'some comment' | 提交文件修改内容 |
| git push | 推送到远程仓库 |
| git pull | 从远程仓库拉取内容 |
git可以使用http和ssh两种方式,ssh方式,其实就是把github或者远程仓库当成ssh的服务器
## programming language
前面介绍了,只用命令没法高效的完成编程工作
## 部署vue项目
- what is vue
- what is deploy
- demo project for quick start
	- what is node & npm
## vue
## node
简单的理解就是可以把js当成像python一样的语言,直接编写.js文件,让前端人员也具备了脱离html的srcipt标签也可以工作的能力,比如网络io,数据库读写,文件读写等,


<!--stackedit_data:
eyJoaXN0b3J5IjpbOTY5OTQ2NjU1LC0yMjE2OTAxMTgsMTUxMT
c3NDY4OSwtNDY3MzYyOTcwLDEwMTkyMTUwMjksLTE0MDU5OTQy
NTgsLTE3OTg3OTI5MCwtMTUzODQ2OTU3OCwxNjg1NDIwNTM0XX
0=
-->