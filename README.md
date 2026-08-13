<div align="center">

# Zack Zhang · 张倬玮

**AI Product Manager / AI Application Builder**

应用统计学背景，关注 AI Agent、RAG、评测与审计自动化。<br>我用产品方法、数据和工程原型，把模型能力变成可验证、可交付的产品体验。

[个人网站](https://portfolio-zack124.vercel.app) · [和我的 AI 分身对话](https://ask-me-career-agent.vercel.app) · [联系我](mailto:zackzhang124@163.com)

</div>

## 关于我

- **产品方向：** AI 应用、Agent 工作流、RAG 与评测体系。
- **工程能力：** 使用 TypeScript / Python 快速搭建完整 Demo，并通过测试、CI 和数据边界验证产品假设。
- **问题偏好：** 喜欢把模糊需求拆成可观察、可评估、可持续迭代的产品系统。
- **求职方向：** AI 产品经理、AI 应用产品与相关实习机会。

## 经历

- **百川智能 · 实习** — 参与医疗 RAG 知识助手，负责知识库构建与检索问答链路（脱敏复刻版见下方 RAG 项目）。
- **东北大学 · 应用统计学 · 2027 届** — 用统计与数据方法做产品判断：评测设计、抽样审计、指标体系。

## 精选项目

### 🤖 [Ask Me — AI 求职数字分身](https://github.com/ZackZhang-AI/ask-me-career-agent)

面向 AI 产品招聘场景的候选人 Agent，让招聘方先快速判断、再按兴趣深入核验。

- **可信回答：** 回答只使用已审核公开知识，保留 Claim-Source 事实对应；可以追问，越界会拒答。
- **内容管线：** 知识统一维护在 `content/`，构建期由 Zod 校验 Claim-Source 引用完整性；8 个 STAR 案例与 9 条审核知识进入公开检索。
- **线上风控：** 请求与 Token 预算、Upstash 跨实例限流、匿名事件记录、紧急开关，密钥只在服务端。
- **技术栈：** `Next.js` `DeepSeek` `Upstash` `Neon` `Vercel Blob`

[在线体验](https://ask-me-career-agent.vercel.app) · [查看仓库](https://github.com/ZackZhang-AI/ask-me-career-agent)

### 📚 [RAG Knowledge Base — 企业级 RAG 知识库](https://github.com/ZackZhang-AI/RAG-Knowledge-Base-System)

百川智能实习期间医疗 RAG 知识助手的脱敏复刻，覆盖从文档进来到答案出去的完整链路。

- **文档处理：** PDF / Word / Excel / PPT 等多格式解析，OCR + 结构分析提取文本、表格与页码元数据。
- **检索问答：** BM25 + 向量混合检索配 Rerank，每条回答可溯源到引用文档的具体段落和页码。
- **自动评测：** 基于知识库自动生成单跳 / 多跳 QA 数据集，按 RAGAS 思路输出忠实度、相关性、召回率多维打分与错误分析报告。
- **工程架构：** `FastAPI` `Vue 3` `Milvus` `MinIO` `Celery + RabbitMQ` `Redis`，RBAC 多用户隔离。

[查看仓库](https://github.com/ZackZhang-AI/RAG-Knowledge-Base-System)

> 更多项目的交互式呈现见 [portfolio](https://portfolio-zack124.vercel.app)（[仓库](https://github.com/ZackZhang-AI/portfolio)）。

## AI Agent 系统

- **[AgentScope](https://github.com/ZackZhang-AI/AgentScope)** `Next.js 16 · PostgreSQL · Playwright`：AI Agent 黑匣子回放器，解释失败、从 Checkpoint 安全分叉、用证据验证修复；90 秒演示免 Key 可复现（v0.3.4）。[在线体验](https://agentscope-harnesslab.vercel.app)
- **[DeepFlow](https://github.com/ZackZhang-AI/DeepFlow)** `DeepSeek · FastAPI · Next.js 16 · Tavily`：多 Agent 深度研究平台，5 分钟产出带 50+ 真实引用的结构化报告，单次成本约 ¥0.8，支持 6 种报告风格与播客 / PPT 产物。

## 求职与审计工具

- **[ai-resume-agent](https://github.com/ZackZhang-AI/ai-resume-agent)** `Python · Multi-Agent`：面向 AI 产品经理求职场景的多 Agent 简历优化系统。
- **[audit-intern-assistant](https://github.com/ZackZhang-AI/audit-intern-assistant)** `Python`：审计资料智能归档与底稿辅助生成。
- **[it-audit-log-sampling-assistant](https://github.com/ZackZhang-AI/it-audit-log-sampling-assistant)** `Python · 数据分析`：从 Excel / CSV 日志中识别异常并生成 IT 审计关注点。

## 效率与创意工具

- **[thirty-minute-brain](https://github.com/ZackZhang-AI/thirty-minute-brain)** `Tauri · React`：记录、整理和回顾 30 分钟思考过程的桌面工作流。
- **[read-later-regret](https://github.com/ZackZhang-AI/read-later-regret)** `Plasmo · React`：减少稍后阅读积压与信息债的浏览器插件。
- **[downloads-butler](https://github.com/ZackZhang-AI/downloads-butler)** `Tauri · React`：先扫描、再建议、确认后移动的本地下载目录整理工具。

## 写作与沉淀

- **[Coding Benchmarks](https://portfolio-zack124.vercel.app/benchmark-coding.html)** — 从函数到产品：13 个 Coding 基准深度解读 × 1 个设计实践。
- **[Benchmark Atlas](https://portfolio-zack124.vercel.app/benchmark-panorama.html)** — 基准的边界：23 个 LLM 基准全景研究。
- **[AI PM Playbook](https://ai-pm-playbook.ok.kimi.link)** — AI 产品经理知识地图。
- **[Prompt to Graph](https://prompt-to-graph.ok.kimi.link/)** — Agent 工程实践报告。
- **[Agent Intel](https://agent-intel.ok.kimi.link)** — Agent 产品格局观察报告。
- **[Eval Handbook](https://portfolio-zack124.vercel.app/eval-handbook.html)** — RAG 评测手册：指标体系、数据集构造、错误分析。

## 我关注的产品问题

- 如何把复杂的 Agent 工作流变成用户能理解和控制的产品体验。
- 如何用评测、日志和事实来源判断 AI 功能是否真正可靠。
- 如何设计安全边界，让自动化既有效率，也保留必要的人类确认。
- 如何用小而完整的 Demo 快速验证需求、交互和技术可行性。

## 技术与方法

`Product Discovery` · `AI Agent` · `RAG` · `Evaluation` · `TypeScript` · `Python` · `Next.js` · `FastAPI` · `Vue 3` · `Tauri` · `Playwright` · `Docker`

## 联系方式

- Email: [zackzhang124@163.com](mailto:zackzhang124@163.com)
- Portfolio: [portfolio-zack124.vercel.app](https://portfolio-zack124.vercel.app)
- GitHub: [github.com/ZackZhang-AI](https://github.com/ZackZhang-AI)
