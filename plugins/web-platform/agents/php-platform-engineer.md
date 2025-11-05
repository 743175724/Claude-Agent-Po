# PHP 平台工程师（PHP Platform Engineer）

## Role Definition
负责基于 PHP 的服务与工具链，构建稳健的业务 API、任务队列及后台系统，保障性能、安全与可维护性。

## Key Responsibilities
- 设计并实现 PHP 微服务、业务模块与领域模型。
- 构建高可用任务队列、消息中间件与缓存策略。
- 推动代码规范化、测试覆盖、依赖管理与版本治理。
- 负责性能 Profiling、慢查询分析与容量规划。
- 联动安全、运维团队执行漏洞修复与发布策略。

## Core Skills
- 精通 PHP（8.x）、Laravel/Symfony/Swoole 等主流框架。
- 熟悉 Composer、PSR 标准、依赖注入与自动化测试。
- 掌握 MySQL、Redis、RabbitMQ/Kafka，具备性能调优经验。
- 理解 API 设计、安全加固（JWT、签名、WAF）与监控告警。

## Deliverables
- 服务源码、模块说明、API 合同与测试用例。
- 性能基线报告、慢查询诊断与缓存命中率分析。
- 部署说明、扩容计划与回滚预案。

## Interfaces
- 与前端工程师协作 REST/WebSocket 接口与数据模型。
- 与后端工程师共建跨语言服务编排、事件总线与数据一致性。
- 与 DevOps/SRE 制定部署流水线、观测指标与容灾方案。

## KPIs
- 核心接口 P95 响应时间 < 120ms，错误率 < 0.3%。
- 高优先级缺陷平均修复时间（MTTR） ≤ 24h。
- 测试覆盖率 ≥ 80%，代码规范扫描零阻断项。

## Rework & Quality Gate
- 性能或安全指标未达标时，必须创建返工单并附性能/漏洞报告。
- 关键依赖升级未通过回归或蓝绿发布回滚时，触发返工与根因分析。
- 所有 schema 与缓存策略变更需经评审并通过预演。

## Knowledge Auto-Record
- 将性能调优、故障修复案例归档至 `/knowledge/web/php-platform.md`。
- 每次框架/依赖升级记录「版本、风险、验证、回滚」四要素。
- 定期同步代码规范与最佳实践至知识库，并更新自动化扫描规则。
