# zookeepr源码阅读指引


## 客户端api设计与实现

[ZooKeeper.java](../zookeeper-server/src/main/java/org/apache/zookeeper/ZooKeeper.java)包含ZooKeeper所有客户端API设计与实现<br>

[ZookeeperMain.java](../zookeeper-server/src/main/java/org/apache/zookeeper/ZooKeeperMain.java)


## 序列化与协议

zookeeper-jute模块

## 网络通信

[NIOServerCnxn.java](../zookeeper-server/src/main/java/org/apache/zookeeper/server/NIOServerCnxn.java)

[NIOServerCnxnFactory.java](../zookeeper-server/src/main/java/org/apache/zookeeper/server/NIOServerCnxnFactory.java)

[NettyServerCnxn.java](../zookeeper-server/src/main/java/org/apache/zookeeper/server/NettyServerCnxn.java)

[NettyServerCnxnFactory.java](../zookeeper-server/src/main/java/org/apache/zookeeper/server/NettyServerCnxnFactory.java)

## Watcher机制

[Watcher.java](../zookeeper-server/src/main/java/org/apache/zookeeper/Watcher.java)

[WatcherEvent.java](../zookeeper-server/src/main/java/org/apache/zookeeper/WatcherEvent.java)

[ClientWatchManager.java](../zookeeper-server/src/main/java/org/apache/zookeeper/ClientWatchManager.java)

[ZKWatchManager.java](../zookeeper-server/src/main/java/org/apache/zookeeper/ZKWatchManager.java)


## 数据与存储

## 请求处理

## Leader选举

ZooKeeper最核心的技术之一

### 选举算法的接口定义
[Election.java](../zookeeper-server/src/main/java/org/apache/zookeeper/server/quorum/Election.java)
### 选举算法的3种实现

[FastLeaderElection.java](src/main/java/org/apache/zookeeper/server/quorum/FastLeaderElection.java)



### 网络通信


## 服务端各角色工作原理

## 权限认证

## JMX相关
ZooKeeper使用JMX来帮助运维人员对ZooKeeper服务器进行监控和管理

## 静态变量定义

## Zookeeper异常定义



