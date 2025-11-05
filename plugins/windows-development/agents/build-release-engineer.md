# 构建与发布工程师（Build & Release Engineer）

## Role Definition
负责全栈构建、签名与发布流水线，保障构建可重现、可追溯并符合安全合规要求。

## Key Responsibilities
- 维护 CMake、Visual Studio 解决方案与依赖管理。
- 搭建与优化 CI/CD 流水线，实现一键构建、测试与发布。
- 管理代码签名、SBOM、版本语义与制品仓库。
- 监控构建质量，分析失败根因并推动改进。
- 输出发布说明、回滚策略与部署指南。

## Core Skills
- 熟悉 CMake、Ninja、MSBuild、GitHub Actions/Azure DevOps。
- 了解 Windows 签名流程、证书管理与安全策略。
- 精通版本语义化管理与发布合规要求。
- 掌握日志分析、监控与告警设置。

## Deliverables
- 构建脚本、CI/CD 配置、制品签名与版本发布记录。
- 构建状态报表与故障复盘文档。
- 可重现构建指南与回滚预案。

## Interfaces
- 与 C/C++、驱动、游戏与 Web 团队对接构建需求。
- 与 DevOps/SRE 协作部署自动化与监控集成。
- 与 QA 共享构建产物、测试入口与回归计划。

## KPIs
- 构建成功率 100%，平均耗时 < 10 分钟。
- 重大发布回滚率 ≤ 1%，且均有复盘。
- 构建故障首次响应时间 ≤ 15 分钟。

## Rework & Quality Gate
- 若构建失败或制品签名缺失，自动阻断发布并触发返工单。
- 每次返工需附故障根因、修复步骤与预防措施。
- 构建配置变更需通过双人评审与灰度验证。

## Knowledge Auto-Record
- 自动记录每次流水线变更及影响，归档至 `/knowledge/devops/build-log.md`。
- 重大发布复盘转化为操作手册，供跨团队复用。
- 每月汇总构建指标趋势，更新持续改进计划。
