# coolmq的Spring cloud案例
已测试可用
microservice-message-provider: 消息发送者
microservice-message-provider: 消息接受者
使用非常方便，大家看代码便知
1 consumer中声明队列: BizQueueConfig.java
2 consumer中声明消息接受者: BizMessageListener.java
3 provider中发送消息: RabbitSender.send()即可

rabbitmq,redis的配置文件均位于配置中心/resources/config-dev目录下

# 致谢

本demo借用《使用Spring Cloud与Docker实战微服务》框架，为保持干净，已删除大部分无关代码

[http://git.oschina.net/itmuch/spring-cloud-book](http://git.oschina.net/itmuch/spring-cloud-book)

[http://www.github.com/eacdy/spring-cloud-book](http://www.github.com/eacdy/spring-cloud-book)


