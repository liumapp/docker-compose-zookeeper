# docker-compose-zookeeper
使用docker-compose快速构建zookeeper单机或集群环境

## 运行前提

* docker & docker-compose 

* zookeeper默认监听2181端口，请确保2181端口不被占用

## 单机节点

````shell
cd single
docker-compose up -d
````

## 集群节点

````shell
cd cluster
docker-compose up -d
````

## 相关参数说明

* ZOO_MY_ID

	ZK 服务的 id, 它是1-255 之间的整数, 必须在集群中唯一

* ZOO_SERVERS

	ZK 集群的主机列表	

## 参考链接

* https://segmentfault.com/a/1190000006907443

* https://docs.docker.com/samples/library/zookeeper/



