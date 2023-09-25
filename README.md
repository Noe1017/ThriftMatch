#### 青春七院 开发者大赛 第一名 作品
一个基于 thrift 实现的进行间匹配和数据存储的轻量级客户端
- 使用生产者消费者模型来对，导入数据池中的玩家进行匹配，避免死锁的发生
- 服务分为三部分：分别是 game，match_system，save_server
- game 为 match_client 端，通过 match.thrift 接口向 match_system 完成添加用户和删除用户的操作
#### 所有者：Noe1017
