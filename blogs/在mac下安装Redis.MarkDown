首先要从官网[http://www.redis.io](http://www.redis.io)上下载所需要版本（或者最新）的redis版本

我下载了3.0.7版本,
[http://download.redis.io/releases/redis-3.0.7.tar.gz](hhttp://download.redis.io/releases/redis-3.0.7.tar.gz)

然后把文件解压，osX下双击或者命令行都可以。

进入目录redis-3.0.7，一般是redis-后面跟版本号  

>$cd redis-3.0.7

用make进行程序的编译安装

>$make

运行即可启动redis服务

>$src/redis-server

>或者 

>$cd src

>$./redis-server