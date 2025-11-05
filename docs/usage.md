# Usage Guide

本指南帮助你以“项目治理 → 领域开发 → 质量沉淀”的方式使用整套智能体团队。

## 1. 发现与激活角色
1. 打开 `.claude-plugin/marketplace.json` 查看插件与角色列表。
2. 根据项目阶段激活对应插件：
   - **Project Governance**：规划目标、梳理架构。
   - **Windows Development / Kernel**：实现与验证系统与驱动模块。
   - **Desktop UI**：负责 UI/UX、IMGUI、ExDUIR 协同。
   - **Reverse Engineering & Security**：处理逆向调研与安全防护。
   - **Game Development**：覆盖 UE/Unity 及跨引擎协同。
   - **Web Platform**：构建控制面板、后端（含 PHP/Python 平台）服务与运维自动化。
   - **Quality & Documentation**：落地测试、返工与知识归档。

## 2. 推荐工作流
1. **项目负责人** 拆解目标、建立任务矩阵并分配给各领域角色。
2. **技术架构师** 定义接口与非功能指标，驱动技术方案评审。
3. 各领域工程师根据角色文件执行职责，并在 `Rework & Quality Gate` 处校验质量。
4. **测试工程师** 根据 `返工单模板` 跟踪缺陷，协调回归验证。
5. **技术文档工程师** 汇总学习记录，更新 `knowledge/` 目录与版本索引。

## 3. 返工与知识沉淀
- 遇到返工触发条件时，使用 `templates/rework-ticket.md` 创建返工单。
- 周期性同步 `templates/weekly-report.md`、`templates/learning-record.md`，构建团队复盘素材。
- 将经验按照角色文件中指定的路径归档到 `knowledge/` 下，例如：
  - `/knowledge/kernel/`：驱动调试与补丁复盘。
  - `/knowledge/ui/`：UI 规范、性能调优案例。
  - `/knowledge/game/`：引擎性能对齐与工具链经验。

## 4. 扩展指南
- 若需新增命令或技能，可在对应插件下建立 `commands/`、`skills/` 目录。
- 增补角色后请更新 `marketplace.json` 与本指南，保持索引一致。
- 推荐在知识库中创建专题目录，例如 `/knowledge/security/incident/`，用于归档安全事件。

## 5. 常见场景
- **跨域联调**：项目负责人协调 C++、驱动、UI 与安全角色，根据返工单执行回归。
- **性能攻坚**：架构师牵头，UE/Unity/IMGUI 工程师协同，QA 输出性能报告并归档。
- **安全演练**：安全工程师与蓝队角色联合执行，DevOps 支持灰度与回滚。

通过上述流程，可以快速搭建自适应的智能体团队，让复杂多域项目具备可追踪、可返工、可沉淀的协作基线。
