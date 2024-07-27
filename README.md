•	基于Boost::asio实现多线程的异步HTTP服务器，各服务间用gRPC通信；
•	客户端使用QNetworkAccessManager进行HTTP通信，QTcpSocket建立 TCP 连接并传输数据流；
•	封装了Redis（缓存验证码并设置过期时间）、MySQL（存储用户信息）连接池；
•	程序设计中，使用了奇异递归模板和单例设计模式。
