# 可以ssh连接的centos镜像

* 账号 ```root```
* 密码 ```88888888```

## 示例
* 运行容器
```
docker run --name centos_ssh -p 2222:22 -d chenqionghe/centos
```
* 连接
```
ssh root@127.0.0.1 -p 2222
```


