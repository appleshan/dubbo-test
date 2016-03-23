[![Build Status](https://travis-ci.org/ofpay/edge.png)](https://travis-ci.org/ofpay/edge)
dubbo-test --- Dubbo Visualized Testing Tool
========================
Welcome to dubbo-test!
dubbo-test是一款用于测试Dubbo接口的开发者测试工具；能够让开发者迅速对自己的dubbo服务进行界面化的测试；

使用指南

1. 在web容器中部署dubbo-test.war；
2. 获取待测dubbo服务的客户端jar包，例如：xx-api.jar
3. 将上述jar包放入${dubbo-test.home}/WEB-INF/third_lib目录中；
4. 修改${dubbo-test.home}/WEB-INF/config.properties，配置待测dubbo服务所在的注册中心；
5. 启动web容器；

![image](https://github.com/ofpay/edge/raw/master/main.jpg)
