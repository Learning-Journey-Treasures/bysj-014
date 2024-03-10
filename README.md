**[点我获取源码](https://x-x.fun/e/VId2fcbe68ue3)💕🤞**

**[点我获取源码+论文](https://x-x.fun/e/NI39de3fb5Zat)💕🤞**

**郑重声明：项目经过本地测试，确保可以运行。由于精力有限，不提供调试服务。项目仅供学习和毕业设计参考~**

#### 1.项目介绍

技术栈+工具：SpringBoot + Vue + MySQL + Maven等

项目角色： 管理员、 普通用户

项目功能：管理员（商品管理、机票管理、网站管理、基础信息等）、普通用户（旅游景点、周边、酒店预订、机票预订、旅游攻略）等

admin-web： web端（可以不使用，admin-api里面有其编译后dist目录的内容，在src/main/webapp下）

admin-api： 管理后端

#### 2.项目部署

- 创建数据库，导入项目中的sql

- 打开IDEA，导入项目admin-web

- 根据本地数据库环境，修改数据库的连接信息 src/main/resources/application.properties 13-16行

- 项目提供了upload资源，下载后，放到项目的upload目录内：src/main/webapp/upload

- 运行项目， http://localhost:8080/travel/index.html  管理员账户密码： admin/admin， 普通用户账号密码： 1234444444444/123456，或者自行注册