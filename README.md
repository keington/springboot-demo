# 微信云托管Spring Boot Demo

## 注意
 + 微信云托管在项目根目录下必须含有Dockerfile（微信云托管本身就是一个Docker集群），是依赖于Dockerfile进行发部署；
 + container.config.json是云托管的配置文件（配置服务所需的大概配置，CPU内存等）；
 + 如果一个项目含有多个工程，每个工程部署一个服务，然后每个工程通过 **公网域名进行调用**（含有安全风险，抓包可以轻易抓到）；
 + 云托管服务之间调用暂不支持内网地址；
 + 云托管可以使用云托管的数据库，可以内网下使用内网；