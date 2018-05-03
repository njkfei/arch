# 问题列表
- dubbo
- spring
- 数据库
- 性能优化
- 分布式事务
- 降级，限流，熔断
- 缓存
- 设计模式
- 线程池
- 锁
- java
- linux
- 机器学习
- 架构设计
- 搜索
- nginx
- IO
- MQ
- 监控报警

# dubbo
- dubbo代码框架
- dubbo如何实现服务发布
- dubbo如何实现服务自动发现
- dubbo优雅降级
- dubbo监控
- dubbo线程池
- dubbo协议设计
- dubbo通信

# spring
- spring框架组成
- 如何自定义元素
- 如何自定义注解
- spring源码分析
- spring aop
- 动态代理
- spring cloud

# 数据库
- 数据库索引原理
- 数据库分库分表
- 数据库连接池
- 数据库mybatis参数
- so_timeout和connect_time是什么意思
- 联合索引，（a,b)建立了几个索引，有几个B树
- 聚集索引，非聚集索引
- 上亿的数据上，新增一列，会发生什么现象
- 数据同步中心RDC
- binlog
- 数据库性能优化，慢查询
- mybatis关键字threshold
- replace into的原理，以及副作用
- insert into on duplicate key 
- cas
- 数据库的锁级别 

# 性能优化
- 如何搞
- 如何理解性能优化

性能优化是设计出来的，不是测试出来的，等测试出来就晚了

# 分布式事务
- 二阶段提交
- 三阶段提交

# 降级，限流，熔断
- 核心链路，非核心链路

# 缓存
- 缓存穿透
- 数据一致性
- 如果缓存不存在，怎么搞
- 使用过哪些redis命令
- 一致性hash
- redis + lua
- java调用lau redis脚本 eval evalsha
- jedis client isBroken重连
- redis数据结构底层存储结构是什么
- redis集中清理过期的key时，会发生什么事情

# 线程池
- 线程池有哪些核心参数
- jedis是线程安全的吗？
- http连接池
- ThreadLocal
- CyclicBarrier CoundDownLatch
- Lock Condition

# 锁
- 偏向锁
- 非偏向锁
- 公平锁
- 非公平锁
- 自旋锁
- 锁消除
- 锁膨胀
- 分布式锁
- 锁分段

# java
- 普通对象与类对象
- java范型，<extend ?> <super ?> T
- sync关键字是否适用于静态方法
- java并发包,源码分析
- java同步器
- invokeall和invokeany
- jvm原理，jmm内存模型
- G1原理，CMS原理
- JVM参数设置多大合理
- java类加载机制
- java异步转同步
- jstack
- jmap
- jstat
- jstatd
- atomic volatile区别
- Collections.unmodifiableCollection使用场景是什么
- RuntimeException

# linux
- swap
- awk,sed,grep,find
- 出现大量的TIME_WAIT意味着什么？

# 机器学习
- 推荐系统原理
- 召回率，正确率
- AUC曲线
- 逻辑回归，SVM原理

# 架构设计
- 高性能设计
- 高可用设计
- 运维设计
- 调用链跟踪
- 监控和报警
- 慢查询

# 搜索
- qps性能
- 建索引性能
- 段合并
- 水平扩展
- 监控

# nginx
- break,last,rewrite
- nginx工作阶段，content rewrite

# IO
- BIO,NIO,AIO
- 推送
- 延迟队列
- http长连接如何搞

# MQ
- 延迟消费

# 监控报警
- 慢查询监控
- 系统监控
- 业务监控
- 进程监控
- 监控大盘
