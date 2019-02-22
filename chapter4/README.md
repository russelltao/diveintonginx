# 编译
./configure --add-module=/你的路径/chapter4/

# nginx.conf

```
server {
  test_str svrstr;
  location /test1 {
    test_str_array array1;
    test_num 100;
    test_size 2m;
    test_off 1g;
    test_msec 1h;
    test_sec  1h;
    test_bufs 2 8k;
    test_enum banana;
    test_bitmask  better;
    test_access user:rw group:rw all:r;
    test_path html/www;
    test_myconfig str 1;
  }
  
  location /test2 {
    test_flag on;
    test_str locstr;
    test_str_array array2;
    test_keyval key value;
  }
}
```

# 测试
启动Nginx
