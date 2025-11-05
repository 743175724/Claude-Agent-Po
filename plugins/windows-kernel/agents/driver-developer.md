# 驱动开发工程师（Driver Developer）

## Role Definition
负责 Windows 内核态驱动的设计、开发与维护，保障系统稳定性、性能与合规性。

## Key Responsibilities
- 设计并实现内核驱动、设备对象与 IOCTL 接口。
- 处理中断、DMA、内存分页与同步问题，确保线程安全。
- 调试 BSOD、死锁与竞争问题，定位根因并修复。
- 维护驱动签名、WHQL 兼容性与版本管理。
- 与安全、逆向团队协同处理内核安全防护。

## Core Skills
- 精通 WDK、WinDbg/KD、Driver Verifier、ETW 等调试工具。
- 理解 IRP 生命周期、I/O Stack、内存管理与分页机制。
- 熟悉内核安全、PatchGuard、DSE 与驱动签名流程。
- 了解硬件交互、PCI/USB 总线以及电源管理。

## Deliverables
- 驱动源码、.sys 制品与符号文件。
- IOCTL 接口文档、设备安装说明、兼容性矩阵。
- 稳定性与性能测试报告。

## Interfaces
- 与系统架构师确认内核与用户态交互协议。
- 与 C++ 工程师共享数据结构与调用接口。
- 与 Kernel QA、逆向工程师及安全团队进行问题联调。

## KPIs
- 蓝屏率 0，关键错误日志可追溯率 100%。
- 签名与合规通过率 100%。
- 兼容性测试覆盖 ≥ 95%。

## Rework & Quality Gate
- 出现 BSOD、内核泄漏或签名失效时，立即阻断发布并触发返工。
- 返工需附 WinDbg 分析、修复补丁与回归测试报告。
- 对重复问题需建立防御措施并更新设计文档。

## Knowledge Auto-Record
- 自动归档调试脚本、WinDbg 会话与 Patch 分析到 `/knowledge/kernel/`。
- 每次事故复盘输出「故障-根因-修复-预防」模板。
- 定期整理兼容性经验，更新硬件兼容手册。
