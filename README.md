## 前言
　　`小火苗项目`    
## 项目介绍

``` 
ihuomiao
├── ihuomiao-common -- SSM框架公共模块
├── ihuomiao-admin -- 后台管理模板
├── ihuomiao-ui -- 前台thymeleaf模板[端口:1000]
├── ihuomiao-config -- 配置中心[端口:1001]
├── ihuomiao-upms -- 用户权限管理系统
|    ├── ihuomiao-upms-common -- upms系统公共模块
|    ├── ihuomiao-upms-dao -- 代码生成模块，无需开发
|    ├── ihuomiao-upms-client -- 集成upms依赖包，提供单点认证、授权、统一会话管理
|    ├── ihuomiao-upms-rpc-api -- rpc接口包
|    ├── ihuomiao-upms-rpc-service -- rpc服务提供者
|    └── ihuomiao-upms-server -- 用户权限系统及SSO服务端[端口:1111]
├── ihuomiao-cms -- 内容管理系统
|    ├── ihuomiao-cms-common -- cms系统公共模块
|    ├── ihuomiao-cms-dao -- 代码生成模块，无需开发
|    ├── ihuomiao-cms-rpc-api -- rpc接口包
|    ├── ihuomiao-cms-rpc-service -- rpc服务提供者
|    ├── ihuomiao-cms-search -- 搜索服务[端口:2221]
|    ├── ihuomiao-cms-admin -- 后台管理[端口:2222]
|    ├── ihuomiao-cms-job -- 消息队列、任务调度等[端口:2223]
|    └── ihuomiao-cms-web -- 网站前台[端口:2224]
├── ihuomiao-pay -- 支付系统
|    ├── ihuomiao-pay-common -- pay系统公共模块
|    ├── ihuomiao-pay-dao -- 代码生成模块，无需开发
|    ├── ihuomiao-pay-rpc-api -- rpc接口包
|    ├── ihuomiao-pay-rpc-service -- rpc服务提供者
|    ├── ihuomiao-pay-sdk -- 开发工具包
|    ├── ihuomiao-pay-admin -- 后台管理[端口:3331]
|    └── ihuomiao-pay-web -- 演示示例[端口:3332]
├── ihuomiao-ucenter -- 用户系统(包括第三方登录)
|    ├── ihuomiao-ucenter-common -- ucenter系统公共模块
|    ├── ihuomiao-ucenter-dao -- 代码生成模块，无需开发
|    ├── ihuomiao-ucenter-rpc-api -- rpc接口包
|    ├── ihuomiao-ucenter-rpc-service -- rpc服务提供者
|    └── ihuomiao-ucenter-web -- 网站前台[端口:4441]
├── ihuomiao-wechat -- 微信系统
|    ├── ihuomiao-wechat-mp -- 微信公众号管理系统
|    |    ├── ihuomiao-wechat-mp-dao -- 代码生成模块，无需开发
|    |    ├── ihuomiao-wechat-mp-service -- 业务逻辑
|    |    └── ihuomiao-wechat-mp-admin -- 后台管理[端口:5551]
|    └── ihuomiao-ucenter-app -- 微信小程序后台
├── ihuomiao-api -- API接口总线系统
|    ├── ihuomiao-api-common -- api系统公共模块
|    ├── ihuomiao-api-rpc-api -- rpc接口包
|    ├── ihuomiao-api-rpc-service -- rpc服务提供者
|    └── ihuomiao-api-server -- api系统服务端[端口:6666]
├── ihuomiao-oss -- 对象存储系统
|    ├── ihuomiao-oss-sdk -- 开发工具包
|    ├── ihuomiao-oss-web -- 前台接口[端口:7771]
|    └── ihuomiao-oss-admin -- 后台管理[端口:7772]
├── ihuomiao-message -- 实时通知系统
|    ├── ihuomiao-message-sdk -- 开发工具包
|    ├── ihuomiao-message-server -- 服务端[端口:8881,SocketIO端口:8882]
|    └── ihuomiao-message-client -- 客户端
├── ihuomiao-shop -- 电子商务系统
└── ihuomiao-demo -- 示例模块(包含一些示例代码等)
     ├── ihuomiao-demo-rpc-api -- rpc接口包
     ├── ihuomiao-demo-rpc-service -- rpc服务提供者
     └── ihuomiao-demo-web -- 演示示例[端口:9999]
```