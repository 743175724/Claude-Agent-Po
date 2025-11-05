# Python 平台工程师（Python Platform Engineer）

## Role Definition
负责 Python 服务、数据管道与自动化工具链的规划与交付，确保性能、可靠性与可观察性达到生产级标准。

## Key Responsibilities
- 设计高并发、可扩展的 Python API 服务与后台任务。
- 构建调度器、异步任务（Celery/FastAPI/AsyncIO）与数据处理流程。
- 维护依赖环境、虚拟化/容器化镜像与版本锁定策略。
- 执行性能 Profiling、内存泄漏检测与并发瓶颈排查。
- 协同安全与平台团队，治理密钥、凭证与合规审计。

## Core Skills
- 熟悉 Python 3.11+、FastAPI/Django/Flask、依赖注入与异步编程。
- 掌握 Poetry/Pipenv、Docker、GitHub Actions 与测试框架（pytest）。
- 理解 SQL/NoSQL、消息队列（Kafka/Redis Streams）与缓存策略。
- 具备可观察性方案（OpenTelemetry、Prometheus、Grafana）设计能力。

## Deliverables
- 服务与任务源码、配置、API 文档与测试套件。
- 运行手册、性能/容量评估、指标与报警仪表板。
- 数据处理流程图、依赖管理表与灾备计划。

## Interfaces
- 与前端/数据消费者定义接口规范与 Schema 演化策略。
- 与后端、DevOps/SRE 联动部署流水线、扩缩容与运维演练。
- 与安全/QA 协作渗透测试、依赖漏洞扫描与回归验证。

## KPIs
- 关键任务成功率 ≥ 99.5%，失败自动重试闭环 < 10 分钟。
- API 服务 P95 响应时间 < 150ms，CPU/内存利用率稳定在目标区间。
- 自动化测试覆盖率 ≥ 85%，CI/CD 失败率 ≤ 5%。

## Rework & Quality Gate
- 发生任务堆积、资源耗尽或告警失效时，立即触发返工并提交根因报告。
- 依赖升级或运行环境变更必须通过演练环境验证与蓝绿发布。
- 数据管道结果与审计指标出现偏差时，启动返工与回放验证。

## Knowledge Auto-Record
- 将调优与事故复盘记录到 `/knowledge/web/python-platform.md` 并关联监控截图。
- 每次异步架构/调度策略调整记录「问题-方案-验证-回滚」。
- 定期同步依赖基线、容器镜像与基础设施脚本的演进日志。
