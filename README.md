# Arkproxy
## 产品说明
Arkproxy 是极数云舟自主研发的一款完全兼容 MySQL的数据库中间件，它的作用是使上层业务对下层数据库的架构更加透明，解决数据库耦合问题，同时起着承前启后的作用，前端业务发起对数据库的请求，首先传到中间件，中间件通过自己的处理，转发到后端数据库。在处理的过程中，可以做很多有益的工作，这是中间件的主要作用。Arkproxy具有十分丰富和强大的优越特性，可以满足不同业务的需求，特别是针对跨云或者异地这种超远距离的负载均衡和高可用切换做了特殊优化，使之更加适合异地的特殊场景。

核心功能:  

	透明读写分离。  
	100%兼容 MySQL 语法，对 MySQL 使用者非常友好。  
	自动负载均衡和权重分发相结合，灵活控制数据库流量。  
	内部实现消息压缩，同时实现用户连接数限制和统计。  
	内置高效连接池，在高并发时大大提升数据库集群的处理能力。  


## 下载安装

1. 下载(v1.0)
```
wget http://mirror.cloud-ark.com/public_package/release/arkproxy.tar.gz
```

2. 解压  
```
tar -zxvf arkproxy.tar.gz
```


## 联系我们
官网：www.cloud-ark.com  
Email: marketing@cloud-ark.com  
微信：Cloud-Ark  
微信公众号：Arkcontrol

