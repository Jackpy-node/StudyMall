# StudyMall


# 环境配置

## 服务器信息

| 服务器           | IP & PORT     | 用户名 | 密码    |
| ---------------- | ------------- | ------ | ------- |
| 本地虚拟机服务器 | 192.168.56.10 | dev    | !dev996 |



## 访问路径

| 项目                | 路径                            | 用户名 |               | 说明                                                         |
| ------------------- | ------------------------------- | ------ | ------------- | ------------------------------------------------------------ |
| Nacos-注册/配置中心 | http://192.168.56.10:8848/nacos | nacos  | nacos         | [home (nacos.io)](https://nacos.io/zh-cn/)                   |
| MinIO-文件服务器    | http://192.168.56.10:9000       | dev    | c~Qo1~qa)b&m@ | [MinIO \|高性能，对Kubernetes友好的对象存储](http://www.minio.org.cn/) |
| RabbitMQ-消息队列   | http://192.168.56.10:15672      | admin  | admin         | [Messaging that just works — RabbitMQ](https://www.rabbitmq.com/) |
| Kibana              | http://192.168.56.10:5671       |        |               |                                                              |



## 后端服务

| 名称         | 服务            | 端口  |
| ------------ | --------------- | ----- |
| 网关服务     | backend-gateway | 8000  |
| 对象存储服务 | file-service    | 19000 |
| 检索服务     | search-service  | 19200 |
| 后台管理服务 | admin-service   | 8082  |
| 优惠服务     | coupon-service  | 9010  |
| 会员服务     | member-service  | 9020  |
| 订单服务     | order-service   | 9030  |
| 商品服务     | product-service | 9040  |
| 仓储服务     | ware-service    | 9050  |





## 服务器软件



| 软件  | 端口               | 用户名   | 密码     |
| ----- | ------------------ | -------- | -------- |
| MySQL | 192.168.56.10:3306 | root     | root     |
| Redis | 192.168.56.10:6379 | 暂时未定 | 暂时未定 |
| Nginx | 192.168.56.10:80   |          |          |
|       |                    |          |          |



## 服务器目录

- **/home/dev**

  主目录

- **/home/dev/java**

  后端java程序

- **/home/dev/data**

  存放docker数据

- **/home/dev/front**

  前端静态程序

- **/home/dev/middle**

  中间件部署目录



## 开发软件清单

| 工具                       | 说明              | 官网                                                         |
| -------------------------- | ----------------- | ------------------------------------------------------------ |
| IDEA                       | 开发IDE           | https://www.jetbrains.com/idea/download                      |
| X-shell                    | Linux远程连接工具 | http://www.netsarang.com/download/software.html              |
| Navicat                    | 数据库连接工具    | http://www.formysql.com/xiazai.html                          |
| AnotherRedisDesktopManager | Redis客户端       | [Releases · qishibo/AnotherRedisDesktopManager · GitHub](https://github.com/qishibo/AnotherRedisDesktopManager/releases) |



## 开发环境

| 工具          | 版本   | 下载                                                         |
| ------------- | ------ | ------------------------------------------------------------ |
| JDK           | 1.8    | https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html |
| Mysql         | 5.7    | https://www.mysql.com/                                       |
| Redis         | 待定   | https://redis.io/download                                    |
| Elasticsearch | 待定   | https://www.elastic.co/downloads                             |
| RabbitMq      | 待定   | http://www.rabbitmq.com/download.html                        |
| nginx         | 待定   | http://nginx.org/en/download.html                            |
| Node          | 12.0.0 | [Node.js Mirror (taobao.org)](https://npm.taobao.org/mirrors/node/v12.0.0/) |
|               |        |                                                              |



## 技术选型

###  后端技术栈

| 技术栈          | 说明           | 官网                                                         |
| --------------- | -------------- | ------------------------------------------------------------ |
| Spring Boot     | 容器+MVC框架   | https://spring.io/projects/spring-boot                       |
| Spring Security | 认证和授权框架 | https://spring.io/projects/spring-security                   |
| MyBatis         | ORM框架        | http://www.mybatis.org/mybatis-3/zh/index.html               |
| Redis           | K-V数据库      | https://redis.io/                                            |
| Docker          | 应用容器引擎   | https://www.docker.com/                                      |
| Lombok          | 简化开发工具   | https://github.com/rzwitserloot/lombok                       |
| FastDFS(备选)   | 文件服务器     |                                                              |
| MinIO(备选)     | 文件服务器     | [MinIO \|高性能，对Kubernetes友好的对象存储](http://www.minio.org.cn/) |



### 前端技术栈

| 技术    | 说明             | 官网                      |
| ------- | ---------------- | ------------------------- |
| Vue     | 前端框架         | https://vuejs.org/        |
| Vuex    | 全局状态管理框架 | https://vuex.vuejs.org/   |
| Element | 前端UI框架       | https://element.eleme.io/ |



## 项目结构
