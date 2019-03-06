# nettyAnalyse
netty源码的自我分析注解



netty包的组成成分:

* buffer  用于数据的传输
* codec
* common
* handler
* resolver 
* tcnative
* transport netty的重要包，里面包含启动类，数据进出口，隧道





netty的几种角色

* bootstrap {ServerBootstrap(服务端), Bootstrap(客户端)}
* channel
* eventLoopGroup
* eventLoop
* channelHandler