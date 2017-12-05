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





















