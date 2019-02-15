# 编译

`./configure --add-module=/你的路径/chapter3/sendfile/`
# nginx.conf
```
   server {
        listen 8080;

        location / {
                mytest;
        }
    }
```
# 测试

* 请求 
`curl 127.0.0.1:8080/`

* 返回

/tmp/test.txt文件内容。*这个文件必须存在*
