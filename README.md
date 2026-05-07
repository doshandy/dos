# 个人简介 · 前端工程师

> 专注企业级数据平台与 AI 产品化集成，擅长将复杂的数据能力转化为易用的前端产品。

- 📫 **联系方式**：sun8630520@126.com
- 🌐 **作品集首页**：<https://doshandy.github.io/dos/>
- 📄 **简历（PDF / Markdown）**：<https://doshandy.github.io/dos/resume/>（在线浏览，⌘P 即可生成 PDF）
- 🧪 **交互 Demo**
  - 🕸 数据血缘可视化（AntV G6）：<https://doshandy.github.io/dos/demos/lineage.html>
  - 🤖 AI Copilot 对话：<https://doshandy.github.io/dos/demos/copilot.html>
  - 📊 数据看板（AntV G2）：<https://doshandy.github.io/dos/demos/charts.html>
  - ⚡ SQL 编辑器（Monaco）：<https://doshandy.github.io/dos/demos/sql-editor.html>

---

## 🎯 核心能力

| 方向 | 关键词 |
|---|---|
| **前端工程化 / 低代码平台** | Vue 3、TypeScript、Monorepo、低代码 Schema → 源码工程化迁移 |
| **数据可视化与交互** | AntV G6 血缘图谱、VXE-Table 大数据表格、Monaco SQL 编辑器 |
| **AI 产品化集成** | LLM Agent 对话、流式响应、自然语言 → SQL / 数据探索 |
| **企业级数据平台架构** | 多国多业务线隔离、权限体系、SQL 多引擎、任务调度与告警 |

---

## 🚀 主推项目：**DataPilot** — 一体化数据协作平台

> **一句话定位**：整合数据集成、数据治理、任务调度与 AI 驱动探索的企业级数据平台，服务多国多业务线。

### 我的角色

- **前端核心开发者（Top 2 贡献者）**，负责多个核心模块从 0 到 1 的前端建设与持续演进。
- 累计贡献 **500+ 次代码提交**，覆盖 8 个核心业务模块。
- 主导并完成了平台整体从「低代码运行时渲染」到「源码工程化构建」的重构迁移，显著提升了构建可控性与可维护性。

### 我主导或深度参与的模块

| 模块 | 职责范围 |
|---|---|
| **DataMap + AI Copilot** | 数据资产目录 + 基于 LLM 的对话式数据探索 Agent，支持自然语言查询、血缘分析、SQL 诊断 |
| **Cerebro SQL 平台** | 多引擎 SQL 编辑执行（Hive/Spark），支持格式化、执行计划、查询诊断、结果分析 |
| **Matrix 数据集成** | 数据源接入、任务配置、同步调度、Tableau 对接 |
| **Schedule / Publish** | 分布式任务调度与发布中心，依赖管理、参数化、审批流 |
| **Table 表管理** | 元数据管理、表开发、分区配置、业务线归属 |
| **DQC 数据质量** | 跨数据源对比、质量模板、SQL 校验 |

### 技术亮点

- 🧠 **AI Copilot 交互设计**：将 LLM 能力封装为可嵌入业务场景的侧边栏 Agent，支持会话上下文、流式输出、场景切换（查表 / 问血缘 / SQL 诊断）。
- 🕸️ **数据血缘可视化**：基于 AntV G6 渲染大规模血缘图谱，支持拖拽、层级折叠、影响链追溯。
- 🛠️ **低代码 → 源码工程化迁移**：将数十个历史低代码页面批量转为 Vue 3 + TypeScript 源码，建立起长期可维护的前端工程体系。
- 🌏 **多国多业务线隔离**：通过域名推断 + 运行时参数隔离，同一套代码支撑 CN / ID / ES / MX 多国独立部署。
- 🔐 **细粒度权限体系**：表级权限、用户分组、临时授权、审计流程。

### 技术栈

`Vue 3` · `TypeScript` · `Ant Design Vue` · `VXE-Table` · `AntV G6` · `Monaco Editor` · `sql-formatter` · `Axios` · `IndexedDB` · `SSE 流式对话`

---

## 🌟 并行主导：**DataLumina** — 数据指标与标签平台

同期主导开发，贡献 **280+ 次代码提交**。聚焦：

- **指标管理**（Metric）：指标定义、授权流程、指标首页
- **标签体系**（Tag）：标签配置、国家隔离、页面权限映射
- **数据探索**（Explore）：即席查询、下载中心、上传能力

同样完成了从低代码到源码的整体迁移。

---

## 🧪 在线可交互 Demo

> 以下 Demo 是对 DataPilot 核心产品形态的极简复刻，纯前端静态页，可直接在浏览器中体验。

### Demo 1：数据血缘可视化 · AntV G6

跨库跨表血缘图谱，支持拖拽、节点点击、上下游影响链自动高亮。

👉 [在线体验](https://doshandy.github.io/dos/demos/lineage.html)

### Demo 2：AI Copilot 对话

模拟自然语言查询数据的对话流，包含预设问答、流式输出动画、SQL 诊断与血缘追溯。

👉 [在线体验](https://doshandy.github.io/dos/demos/copilot.html)

### Demo 3：数据看板 · AntV G2

KPI 卡片 + 多图表组合（折线 / 环形 / 柱状 / 热力），与暗色 UI 风格统一。

👉 [在线体验](https://doshandy.github.io/dos/demos/charts.html)

### Demo 4：SQL 编辑器 · Monaco Editor

完整的 SQL IDE 体验：语法高亮、自动补全、`Cmd/Ctrl+Enter` 执行、`Shift+Alt+F` 格式化、执行计划、运行日志、结果预览。

👉 [在线体验](https://doshandy.github.io/dos/demos/sql-editor.html)

---

## 📬 联系

- Email：**sun8630520@126.com**
- 欢迎就数据平台、AI 集成、前端工程化等话题交流。
