export  GOPATH=/gopath1/src



cd /gopath1/src/restful-json/tns-restful-json-api-master/myRestFul-v3-token/



浏览器访问 http://172.16.10.18

用户名密码 yandun  yandun



跳转到一个发布文章的页面

http://172.16.10.18/myweb/WBlog.html



发布完成后 输入下面页面可以看见刚刚发布的内容

http://172.16.10.18/myweb/Home.html



172.16.10.18/myweb/Home.html

后台url :

http://172.16.10.18/index.html

数据库管理员 账号:root 密码webdemo

mysql -uroot -h172.16.10.18 -p'webdemo'

mysql -hlocalhost -p

password

webdemo

grant all privileges on . to 'root'@'172.16.10.18' identified by 'webdemo';

Received #1045 error from MySQL server: "Access denied for user 'root'@'172.16.10.18' (using password: NO)"