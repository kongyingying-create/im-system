# im-system
基于 SpringBoot + Netty + Redis + RabbitMQ 的高性能即时通讯服务

## 技术栈
- SpringBoot
- Netty / WebSocket
- Redis
- RabbitMQ
- Maven

## 核心功能
- 基于 Netty 实现 WebSocket 长连接通信
- 用户登录与在线状态管理
- 全局消息广播
- Redis 缓存维护在线用户
- RabbitMQ 异步消息处理
- 客户端上下线自动管理

## 项目亮点
- 掌握 Netty 事件驱动模型与高性能网络编程
- 结合 Redis 与 RabbitMQ 实现异步消息架构
- 完整实现长连接会话管理与异常容错
