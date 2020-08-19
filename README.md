# rpc-spring-boot-starter
利用netty实现的rpc框架
- 支持Java序列化和protobuf序列化协议
- 支持多种客户端负载均衡（随机、轮询、加权轮询和平滑加权轮询）算法


### todo list
1. 客户端增加本地服务列表缓存，减少查询zookeeper次数提高性能
2. 并发高时端口号还没被回收另一个线程发起连接提示端口号被占用的问题(客户端和服务端建立长连接解决)
3. 序列化方式利用spi优化
4. 服务端异步多线程处理请求
