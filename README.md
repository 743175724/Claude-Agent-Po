# My Agents Project

围绕 Windows 驱动、C/C++ 系统开发、UI 渲染、逆向安全、游戏引擎、Web 平台与质量治理打造的专业级 Claude 智能体团队蓝图。每个角色均配套角色定位、职责、技能、交付、接口、KPI、返工机制与知识沉淀模式，适用于多域协同项目。

## 目录结构
```
my-agents-project/
├── .claude-plugin/
│   └── marketplace.json
├── docs/
│   └── usage.md
├── knowledge/
├── plugins/
│   ├── project-governance/
│   │   └── agents/
│   ├── windows-development/
│   │   └── agents/
│   ├── windows-kernel/
│   │   └── agents/
│   ├── desktop-ui/
│   │   └── agents/
│   ├── reverse-engineering/
│   │   └── agents/
│   ├── game-development/
│   │   └── agents/
│   ├── web-platform/
│   │   └── agents/
│   └── quality-operations/
│       └── agents/
├── templates/
└── README.md
```

## 角色一览
- **项目治理层**：项目负责人、技术架构师
- **Windows 系统开发**：C/C++ 系统工程师、构建与发布工程师
- **Windows 内核**：驱动开发工程师、Kernel QA 与合规工程师
- **桌面 UI**：UI/UX 设计师、IMGUI 工程师、ExDUIR 工程师
- **逆向与安全**：逆向分析工程师、安全工程师（Anti-Tamper）、安全测试工程师（Blue Team）
- **游戏引擎**：虚幻引擎工程师、Unity 工程师、跨引擎技术总监
- **Web 平台**：前端工程师、后端工程师、PHP 平台工程师、Python 平台工程师、DevOps/SRE 工程师
- **质量与文档**：测试工程师、技术文档工程师

每个角色文件均包含返工触发条件与自动学习记录机制，可直接用于智能体配置或团队流程对齐。

## 快速开始
1. 查看 `.claude-plugin/marketplace.json` 获取插件与角色概览。
2. 阅读 `docs/usage.md` 了解推荐的角色协同与知识沉淀流程。
3. 在 `templates/` 中套用返工单、周报与学习记录模板，结合 `knowledge/` 目录建立专属知识库。
4. 按需扩展 `plugins/` 目录，添加命令、技能或更多角色。

## 知识沉淀
- 所有角色文件的 `Knowledge Auto-Record` 部分指向对应目录，例如 `/knowledge/ui/`、`/knowledge/game/`。
- 在每次迭代结束前，将实践经验整理为 Markdown 文件并归档，保持知识库持续演进。

## 贡献指南
欢迎根据项目实践补充命令、技能或更多领域的角色定义。新增内容请同步更新 `marketplace.json` 与相关文档，确保团队成员可快速发现并应用。
