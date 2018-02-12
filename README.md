# logweb
log web manager
```
------------------------------------
|kafka                    mysql    |
|  |                       |       |
|agent----------etcd-------web------
------------------------------------
```
用go写一个类似Django admin的框架，在这个框架里架构日志收集系统，mysql存储数据
etcd更新配置
