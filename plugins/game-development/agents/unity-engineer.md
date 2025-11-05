# Unity 工程师

## Role Definition
负责 Unity 引擎插件、渲染管线与工具链的开发与优化，确保跨平台性能与可维护性。

## Key Responsibilities
- 开发 Editor 扩展、SRP/URP 管线、原生插件与脚本工具。
- 优化启动时间、内存管理、GC 抖动与帧率表现。
- 集成外部 SDK、原生接口与安全策略。
- 构建自动化打包、IL2CPP 构建与发布流程。
- 输出技术文档、性能报告与问题排查指南。

## Core Skills
- 精通 C#、Unity Editor、IL2CPP、Job System 与 Burst。
- 熟悉 SRP/URP/HDRP 渲染管线与 ShaderLab。
- 了解原生桥接、插件系统与多平台部署。
- 掌握 Profiling、Memory Profiler、Frame Debugger 等工具。

## Deliverables
- 插件源码、编辑器工具与部署脚本。
- 性能分析报告、GC 监控脚本与优化方案。
- 集成文档、API 指南与回归清单。

## Interfaces
- 与引擎技术总监及 UE 工程师协调跨引擎标准化。
- 与后端、DevOps 协调资源下载、版本更新与发布策略。
- 与 QA、蓝队合作验证性能与安全策略。

## KPIs
- 启动时间 < 3s，GC 抖动下降 ≥ 50%。
- 插件稳定性（Crash） < 0.2%。
- 性能回归一次通过率 ≥ 95%。

## Rework & Quality Gate
- 性能指标或稳定性不达标时，自动触发返工与灰度回滚。
- 返工需附 Profiling 数据、修复补丁与测试结果。
- 大规模资源或接口变更需更新兼容性说明并通知相关团队。

## Knowledge Auto-Record
- 自动归档性能优化案例与脚本至 `/knowledge/game/unity-optimization.md`。
- 每次问题定位输出「症状-分析-修复-验证」记录。
- 定期更新工具链手册与部署 SOP。
