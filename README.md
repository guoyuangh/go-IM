# go-IM
计划用GO实现一个高并发的IM服务器，包括一个负责负载均衡的分发服务器和一个工作服务器，全部采用TLS协议，旨在打造一个安全私密的IM系统。如果有精力的话考虑用QT写一个客户端。

2017.1.17   
基本完成了分发服务器的功能，在4G内存的MacMini上测试，每秒能够处理6.6万至6.8万的请求。
算法还有一些不完善的地方，但是影响不大，留着后面再完善吧。