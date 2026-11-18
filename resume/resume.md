# 孙伟 · 前端工程师（数据平台 / AI 产品化方向）

> 专注企业级数据平台与 AI 产品化集成，擅长把复杂的数据能力转化为易用的前端产品。

| | |
| --- | --- |
| 城市 | 北京 |
| 求职意向 | 资深前端 / 数据平台前端 / AI 应用前端 / Tech Lead |
| 邮箱 | [sun8630520@126.com](mailto:sun8630520@126.com) |
| 手机 | 13121587622 |
| 在线作品集 | [doshandy.github.io/dos](https://doshandy.github.io/dos/) |
| GitHub | [github.com/doshandy](https://github.com/doshandy) |

---

## 个人简介

资深前端工程师，主技术栈 **Vue 3 + TypeScript**。多年深耕**企业级数据平台**与 **AI 产品化集成**：从数据集成、SQL 平台、任务调度，到数据资产目录与 AI 对话探索，覆盖完整数据生命周期前端建设。

在主推项目 [DataPilot](#-主推项目datapilot--一体化数据协作平台) 中主导 / 深度参与 8 个核心模块；同期并行主导 [DataLumina](#-并行主导datalumina--数据指标与标签平台)。两个平台都由我牵头完成了**从「低代码运行时渲染」到「源码工程化构建」**的整体重构迁移。

擅长：
- **数据可视化交互**：AntV G6 大规模血缘图谱、VXE-Table 大数据表格、Monaco SQL 编辑器
- **AI 前端工程化**：LLM Agent 对话设计、流式响应、自然语言 → SQL、上下文 / 场景切换
- **多国多业务线产品**：同一套代码支撑 CN / ID / ES / MX 四个独立部署，权限 / 国家 / 语言全维度隔离
- **前端工程化体系**：Vue 3 + TS + Monorepo、CI/CD、组件库与脚手架、低代码 → 源码迁移

---

## 核心能力

| 方向 | 关键词 |
| --- | --- |
| **前端工程化 / 低代码平台** | Vue 3 · TypeScript · Monorepo · 低代码 Schema → 源码工程化迁移 |
| **数据可视化与交互** | AntV G6 血缘图谱 · VXE-Table 大数据表格 · Monaco SQL 编辑器 · AntV G2 |
| **AI 产品化集成** | LLM Agent 对话 · SSE 流式响应 · 自然语言 → SQL · 数据探索 |
| **企业级数据平台架构** | 多国多业务线隔离 · 细粒度权限 · SQL 多引擎 · 任务调度 / 告警 |

---

## 工作经历

### 某金融科技公司 · 资深前端工程师 / 模块负责人

> 公司主营海内外消费金融业务，前端覆盖 C 端 H5、运营后台、数据平台、客服 IM、海外多语言产品等多条产品线。我在数据平台与 AI 产品化方向长期投入，是这两个方向的核心建设者之一。

#### 🚀 主推项目：DataPilot — 一体化数据协作平台

> 整合数据集成、数据治理、任务调度与 AI 驱动探索的企业级数据平台，服务多国多业务线，涵盖整个数据生命周期。

**我的角色**

- **前端核心开发者**，覆盖 8 个核心业务模块的从 0 到 1 建设与持续演进
- **主导平台整体重构**：从「低代码运行时渲染」迁移到「源码工程化构建」，显著提升构建可控性、性能与可维护性
- 多国多业务线（CN / ID / ES / MX）独立部署的前端架构主导者

**主导 / 深度参与的模块**

| 模块 | 职责范围 |
| --- | --- |
| **DataMap + AI Copilot** | 数据资产目录 + 基于 LLM 的对话式 Agent，支持自然语言查询、血缘分析、SQL 诊断 |
| **Cerebro SQL 平台** | 多引擎 SQL 编辑执行（Hive / Spark），格式化、执行计划、查询诊断、结果分析 |
| **Matrix 数据集成** | 数据源接入、任务配置、同步调度、Tableau 对接 |
| **Schedule / Publish** | 分布式任务调度与发布中心，依赖管理、参数化、审批流 |
| **Table 表管理** | 元数据管理、表开发、分区配置、业务线归属 |
| **DQC 数据质量** | 跨数据源对比、质量模板、SQL 校验 |

**技术亮点**

- 🧠 **AI Copilot 交互设计**：把 LLM 能力封装为可嵌入业务场景的侧边栏 Agent，支持会话上下文、SSE 流式输出、场景切换（查表 / 问血缘 / SQL 诊断）
- 🕸️ **数据血缘可视化**：基于 AntV G6 渲染大规模血缘图谱，支持拖拽、层级折叠、上下游影响链追溯
- 🛠️ **低代码 → 源码工程化迁移**：把数十个历史低代码页面批量转为 Vue 3 + TypeScript 源码，建立长期可维护的前端工程体系（构建 / Lint / 测试 / 发布）
- 🌏 **多国多业务线隔离**：通过域名推断 + 运行时参数隔离，同一套代码支撑 CN / ID / ES / MX 多国独立部署
- 🔐 **细粒度权限体系**：表级权限、用户分组、临时授权、审计流程
- ⚡ **大数据表格 / SQL 编辑器**：基于 VXE-Table + Monaco Editor 构建专业级数据消费体验，支持万行数据流畅滚动、SQL 智能补全 / 格式化 / 执行计划

**技术栈**：`Vue 3` `TypeScript` `Ant Design Vue` `VXE-Table` `AntV G6` `Monaco Editor` `sql-formatter` `Axios` `IndexedDB` `SSE 流式对话`

#### 🌟 并行主导：DataLumina — 数据指标与标签平台

> 与 DataPilot 同期主导开发。

聚焦三大能力：

- **指标管理 (Metric)**：指标定义、授权流程、指标首页
- **标签体系 (Tag)**：标签配置、国家隔离、页面权限映射
- **数据探索 (Explore)**：即席查询、下载中心、上传能力

同样完成了从低代码到源码的整体迁移，与 DataPilot 共享一套底层组件与权限体系。

#### 🧰 前端基础设施 / 协作

- **共享组件库**：跨平台沉淀通用业务组件（数据表格、SQL 编辑器、血缘图、AI Copilot 侧边栏），多平台复用
- **CI / CD 与质量门**：参与建设前端 Pipeline（Lint / 单测 / 类型检查 / 构建产物体积守门），关联 Code Review 机制
- **新人 mentor 与技术评审**：参与多名同事的成长辅导，主导关键设计的技术评审

---

## 在线可交互 Demo

> 可在浏览器中直接体验 DataPilot 的核心交互。

| Demo | 技术 | 链接 |
| --- | --- | --- |
| 🕸 数据血缘可视化 | AntV G6 4.x | [lineage.html](https://doshandy.github.io/dos/demos/lineage.html) |
| 🤖 AI Copilot 对话 | SSE 流式 + 场景切换 | [copilot.html](https://doshandy.github.io/dos/demos/copilot.html) |
| 📊 数据看板 | AntV G2 5.x | [charts.html](https://doshandy.github.io/dos/demos/charts.html) |
| ⚡ SQL 编辑器 | Monaco + sql-formatter | [sql-editor.html](https://doshandy.github.io/dos/demos/sql-editor.html) |

---

## 教育背景

| 学校 | 学位 / 专业 | 时间 |
| --- | --- | --- |
| 太原理工大学 | 本科 / 软件工程 | 2012 — 2016 |

---

## 技能清单

- **语言**：TypeScript / JavaScript（精通）· HTML / CSS（精通）· Node.js（熟练）
- **框架**：Vue 2/3（精通源码与生态）· Vue Router / Pinia / Vuex（精通）· React（熟悉）
- **数据可视化**：AntV G6（精通血缘 / 关系图） · AntV G2 · ECharts · Canvas / WebGL（熟悉）
- **数据 / 编辑器**：VXE-Table（万行级数据表）· Monaco Editor（SQL IDE）· sql-formatter
- **AI 工程化**：OpenAI / Anthropic / SSE 流式 / 多场景 Agent · 自然语言 → SQL · Prompt 工程
- **构建工具**：Vite / Webpack / Rollup / esbuild · pnpm Monorepo
- **测试 / 工具链**：Vitest / Jest · ESLint flat config · Husky + lint-staged · GitHub Actions
- **协作**：技术评审 · Code Review 机制设计 · 新人 mentor

---

## 求职偏好

- 偏好可以同时打磨**业务深度 + 平台能力 + AI 工程化**的岗位
- 北京优先，远程 / Hybrid 也接受
- 喜欢看得见摸得着的事：性能数字、用户体验、CI 时间、Bug 数量等可量化指标
- 期望团队：技术氛围浓厚、Code Review 严格、对前端工程化有持续投入

---

> 📄 **PDF 版**：浏览器打开 [doshandy.github.io/dos/resume/](https://doshandy.github.io/dos/resume/) → ⌘P / Ctrl+P → 选「保存为 PDF」即可。
