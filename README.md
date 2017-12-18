# spring-cloud-config-file
基于springcloud搭建的统一配置平台配置文件地址
使用URL查看指定配置文件内容的方法： http://{configserver}:{configserver.port}/{name}/{profile}

例如我们要查看 myconfigclient-dev.properties 则请求的地址为：http://localhost:8888/myconfigclient/dev 返回的信息按优先顺序包括：myconfigclient-dev.properties、application-dev.properties 和 application.properties 因为 application 被框架认为默认配置文件。
