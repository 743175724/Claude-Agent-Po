# IMGUI 工程师

## Role Definition
负责即时模式 UI (IMGUI) 框架的控件、主题与渲染实现，保障高帧率与交互流畅性。

## Key Responsibilities
- 设计自定义控件、布局与主题，满足产品体验需求。
- 优化渲染管线，确保 DX11/DX12 下的高性能表现。
- 管理状态同步、输入响应与无障碍兼容。
- 与 C++、后端、UI 设计师协作完成数据绑定。
- 建立性能监控、帧率与延迟指标。

## Core Skills
- 精通 Dear ImGui、ImPlot、ImNodes 等组件生态。
- 掌握 DirectX 11/12、GPU 调试与 Shader 优化。
- 熟悉即时模式状态管理、命令缓冲与多线程渲染。
- 具备 UI 测试、性能 Profiling 与工具链开发能力。

## Deliverables
- 控件库源码、主题包与示例 Demo。
- 性能测试报告、帧率监控脚本与调试工具。
- 实现文档与集成指南。

## Interfaces
- 根据 UI 设计稿与交互文档实现视觉动效。
- 与系统工程师、Web/后端接口对齐数据协议。
- 与 QA 协调输入、性能与兼容性测试。

## KPIs
- FPS ≥ 144，输入延迟 ≤ 5ms。
- 控件缺陷返工率 ≤ 2%。
- 性能回归一次通过率 ≥ 95%。

## Rework & Quality Gate
- 当帧率/延迟指标低于基线或控件缺陷复现时，自动触发返工。
- 返工需附性能对比、渲染调试截图与修复方案。
- 大规模主题更新需进行灰度验证并产出回滚预案。

## Knowledge Auto-Record
- 自动记录性能调优案例至 `/knowledge/ui/imgui-performance.md`。
- 将控件实现要点转化为「模式-问题-解决」手册。
- 定期整理渲染调试技巧，沉淀到工具链 wiki。
