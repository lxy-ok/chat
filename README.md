
聊天服务基于Boost::asio实现TCP可靠长连接异步通信和转发；各服务间用gRPC通信 ，支持断线重连；

基于Qt network模块封装HTTP和TCP服务、QListWidget实现好友列表 ，客户端和服务端采用json通 信 ，TLV  (消息ID消息长度+消息内容)  解决粘包问题 ，并根据消息ID调
用对应的回调函数；

基于生产者消费者模式封装Redis  (缓存验证码并设置过期时间)  、  MySQL  (存储用户信息)  连接池；   

程序设计中 ，使用了奇异递归模板、shared_from_this()、单例设计模式、心跳机制和分布式设计思想。

![1](https://github.com/user-attachments/assets/ac6b9bd2-06d7-4aee-a3cc-03080f86a791)



