# 编译
./configure --add-module=/你的路径/chapter3/helloworld/

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
curl 127.0.0.1:8080/
