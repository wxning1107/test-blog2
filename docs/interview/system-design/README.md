# 高并发系统设计 40 问

::: tip

本课程理论知识偏多，不适合零基础。更像是总结性的思路。也比较适合放在架构这一层

:::

- [开篇-为什么你要学习高并发系统设计](./00/)
- [01丨基础篇](./01/)
    - [01丨高并发系统：它的通用设计方法是什么?](./01/01.md)
    - [02丨架构分层：我们为什么一定要这么做？](./01/02.md)
    - [03丨系统设计目标 1：如何提升系统性能？](./01/03.md)
    - [04丨系统设计目标 2：系统怎样做到高可用？](./01/04.md)
    - [05丨系统设计目标 3：如何让系统易于扩展？](./01/05.md)
    - [06丨面试现场第 1 期：当问到组件实现原理时，面试官是在刁难你吗？](./01/06.md)

- [02丨演进篇-数据库](./02/)
    - [07丨池化技术：如何减少频繁创建数据库连接的性能损耗？](./02/01.md)
    - [08丨数据库优化方案 1：查询请求增加时，如何做主从分离？](./02/02.md)
    - [09丨数据库优化方案 2：写入数据量增加时，如何实现分库分表？](./02/03.md)
    - [10丨发号器：如何保证分库分表后 ID 的全局唯一性？](./02/04.md)
    - [11丨NoSQL：在高并发场景下，数据库和 NoSQL 如何做到互补？](./02/05.md)

- [03丨演进篇-缓存](./03/)
    - [12丨缓存：数据库成为瓶颈后，动态数据的查询要如何加速？](./03/01.md)
    - [13丨缓存的使用姿势 1：如何选择缓存的读写策略？](./03/02.md)
    - [14丨缓存的使用姿势 2：缓存如何做到高可用？](./03/03.md)
    - [15丨缓存的使用姿势 3：缓存穿透了怎么办？](./03/04.md)
    - [16丨CDN：静态资源如何加速？](./03/05.md)
    - [加餐丨数据的迁移应该如何做？](./03/06.md)
- [04丨演进篇-消息队列](./04/)
    - [17丨消息队列：秒杀时如何处理每秒上万次的下单请求？](./04/01.md)
    - [18丨消息投递：如何保证消息仅仅被消费一次？](./04/02.md)
    - [19丨消息队列：如何降低消息队列系统中消息的延迟？](./04/03.md)
    - [20丨面试现场第 2 期：当问到项目经历时，面试官究竟想要了解什么？](./04/04.md)
    - [期中测试丨10 道高并发系统设计题目自测](./04/05.md)
- [05丨演进篇-分布式服务](./05/)
    - [21丨系统架构：每秒 1 万次请求的系统要做服务化拆分吗？](./05/01.md)
    - [22丨微服务架构：微服务化后，系统架构要如何改造？](./05/02.md)
    - [23丨RPC框架：10 万 QPS 下如何实现毫秒级的服务调用？](./05/03.md)
    - [24丨注册中心：分布式系统如何寻址？](./05/04.md)
    - [25丨分布式 Trace：横跨几十个分布式组件的慢请求要如何排查？](./05/05.md)
    - [26丨负载均衡：怎样提升系统的横向扩展能力？](./05/06.md)
    - [27丨API 网关：系统的门面要如何做呢？](./05/07.md)
    - [28丨多机房部署：跨地域的分布式系统如何做？](./05/08.md)
    - [29丨ServiceMesh：如何屏蔽服务化系统的服务治理细节？](./05/09.md)
- [06丨演进篇-维护](./06/)
    - [30丨给系统加上眼睛：服务端监控要怎么做？](./06/01.md)
    - [31丨应用性能管理：用户的使用体验应该如何监控？](./06/02.md)
    - [32丨压力测试：怎样设计全链路压力测试平台？](./06/03.md)
    - [33丨配置管理：成千上万的配置项要如何管理？](./06/04.md)
    - [34丨降级熔断：如何屏蔽非核心系统故障的影响？](./06/05.md)
    - [35丨流量控制：高并发系统中我们如何操纵流量？](./06/06.md)
    - [36丨面试现场第 3 期：你要如何准备一场技术面试呢？](./06/07.md)
- [07丨实战篇](./07/)
    - [37丨计数系统设计 1：面对海量数据的计数器要如何做？](./07/01.md)
    - [38丨计数系统设计 2：50 万 QPS 下如何设计未读数系统？](./07/02.md)
    - [39丨信息流设计 1：通用信息流系统的推模式要如何做？](./07/03.md)
    - [40丨信息流设计 2：通用信息流系统的拉模式要如何做？](./07/04.md)
