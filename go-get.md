报错信息

```
package golang.org/x/net/context: unrecognized import path "golang.org/x/net/con                                                      text" (https fetch: Get https://golang.org/x/net/context?go-get=1: dial tcp 216.                                                      239.37.1:443: connectex: A connection attempt failed because the connected party                                                       did not properly respond after a period of time, or established connection fail                                                      ed because connected host has failed to respond.)

```

使用github上的镜像库


https://github.com/golang/net

https://golang.org/x/net

二者是一样的

解决：
在gopath src 下 创建目录
golang.org/x
进入目录
git clone https://github.com/golang/net.git


再次 go get github.com/mattn/go-sqlite3


报错如下
```
exec: "gcc": executable file not found in %PATH%
```

解决 ：

安装 tdm-gcc-5.1.0-3

重新打开一个终端


再次执行

go get github.com/mattn/go-sqlite3




sqlite3 安装

Sqlite3文件下载：

1.下载 sqlite-dll-win32-x86-3140100

2.下载 sqlite-tools-win32-x86-3140100

安装：

先在C盘建一个文件夹 sqlite，

1.把 sqlite-dll-win32-x86-3140100 中解压出来的两个文件（sqlite3.def 和 sqlite3.dll）复制到刚才新建的目录（C:\sqlite）中

2.把 sqlite-tools-win32-x86-3140100 中解压出来的文件 sqlite3.exe 复制到C:\sqlite 目录中

3.添加系统环境变量， 在Path变量值后面添加 C:\sqlite（分号不要忘记了），如下图所示：


sqlite3 --version













