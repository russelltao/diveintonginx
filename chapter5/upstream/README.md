# 编译
./configure --add-module=/你的路径/chapter5/upstream/

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

`HelloWorld`
