<div align="center">

# jiuyier369-design

### AI 应用探索 · 产品思考 · Agent 协作开发

从真实问题出发，把需求、产品决策、用户反馈与工程成果连接起来。

[查看核心项目](https://github.com/jiuyier369-design/job-copilot) · [查看个人网站](https://github.com/jiuyier369-design/portfolio-site)

</div>

---

## 关于我

我正在探索 AI 应用产品与 Agent 协作开发。项目中，我负责场景选择、功能取舍、用户流程、试用反馈和最终验收判断，并借助 Codex、WorkBuddy 等 Agent 推进实现。

我关注的是：产品解决了什么问题、用户如何核对结果，以及哪些能力已有证据、哪些仍需完善。

## 项目与作品

| 项目 | 解决的问题 | 我承担的工作 | 当前进度 |
| --- | --- | --- | --- |
| **[Job Copilot](https://github.com/jiuyier369-design/job-copilot)** | 将个人画像、JD 核对与有来源的简历建议连接起来 | 需求定义、证据边界、Agent 分工、试用与报告质量审查 | 持续完善中；已有工程成果，尚未正式上线 |
| **[Portfolio Site](https://github.com/jiuyier369-design/portfolio-site)** | 让招聘者集中查看个人介绍、项目案例与代码成果 | 信息结构、展示内容核对、页面反馈与公开范围 | 基础页面与静态导出完成；内容和部署待完善 |

### Job Copilot · AI 求职决策工具

个人画像 → JD 拆解与核对 → 经历证据确认 → 带引用的分析报告。

项目采用 Next.js、Supabase 和 DeepSeek，包含异步队列、状态恢复及证据校验设计。公开快照的 281 项本地测试通过；完整 v2 流程、真实报告质量和生产部署仍在完善。

**[项目介绍与截图](https://github.com/jiuyier369-design/job-copilot#页面截图) · [产品决策](https://github.com/jiuyier369-design/job-copilot/blob/main/docs/PRODUCT.md) · [架构](https://github.com/jiuyier369-design/job-copilot/blob/main/docs/ARCHITECTURE.md)**

### Portfolio Site · 个人网站与作品集

个人首页、公开简历、项目案例和 GitHub 导航；使用独立仓库维护。目前已有基础展示页面和静态构建验证，不连接 Job Copilot 的真实分析接口。

**[网站介绍与概念封面](https://github.com/jiuyier369-design/portfolio-site) · [开发交接](https://github.com/jiuyier369-design/portfolio-site/blob/main/AGENT_HANDOFF.md)**

## 我的工作方式

**发现问题 → 明确范围 → 设计流程 → 拆解 Agent 任务 → 用户试用 → 核对验收 → 迭代。**

代码由 AI Agent 辅助实现；本人负责产品决策与协作组织，实际实现者和审查者在项目中分别记录。自动校验与本地测试不等于真实报告质量或生产验收。

---

建议先看 Job Copilot 的简介和截图，再读产品与架构说明。两个置顶仓库提供更完整的工程证据。

<sub>状态更新：2026-10-04 · 项目持续完善中</sub>
