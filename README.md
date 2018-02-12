# logweb
log web manager
```
----------------------------------------
|kafka                    mysql        |
|  |                       |           |
|agent----------etcd-------web（Beego）-
----------------------------------------
```
用go写一个类似Django admin的框架，在这个框架里架构日志收集系统，mysql存储数据
etcd更新配置

### 开启etcd

```
cd etcd3.3/
./etcd
```

启动logweb

```
git clone https://github.com/ningxin1718/logweb.git
cd logweb/main 
go build 
运行
./main
http server Running on http://127.0.0.1:8080
```

