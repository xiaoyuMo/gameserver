# 分布式百万在线量级游戏服务器框架
------
* base项目
	>主要的网络库
* auth项目
	>登录服
* sm项目
	>场景服管理
* scene项目
	>场景服
* proto项目
	>传送的相关协议
## 服务器主要采用了netty框架处理socket连接
## 采用protobuf作为发送消息序列化格式
## 使用disruptor框架去做端口消息的多线程同步
	

