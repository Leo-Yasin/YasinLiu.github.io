# YasinLiu.github.io
YasinLiu的个人主页
# 刘宇轩 Yasin Liu

**求职方向：AI Agent 开发**

- 📧 邮箱：lyx1499123312@163.com
- 📱 电话：15155383970
- 📍 地点：深圳 / 香港
- 🌐 语言：CET-6 · IELTS 6.5

---

## 教育背景

### 香港理工大学（The Hong Kong Polytechnic University）

**Computer Science (Blockchain)**  
硕士在读 · 2027 届

### 杭州师范大学

**软件工程 · 学士**

- 专业排名：2 / 50（前 4%）
- 加权平均分：87 / 100
- 优秀毕业生
- 浙江省政府奖学金
- 中共党员

---

## 专业技能

### AI / Agent

- RAG
- Multi-Agent
- ReAct
- Reflection
- Memory
- LoRA 微调

### 编程语言与工具

- C++
- Python
- Git
- LlamaIndex
- Milvus
- LLaMA-Factory

### 前端开发

- HTML / CSS / JavaScript
- TypeScript
- React / Next.js
- ECharts

### AI 编程

- Codex
- Claude Code
- 用于代码生成、调试、重构与技术学习

---

## 实习经历

### 博彦物联科技（北京）有限公司

**AI 算法工程师（实习）**

- **Agent 能力研发：**  
  基于 ReAct、Reflection 与 Memory 机制设计多智能体工作流，完成任务拆解、Agent 协作、检索结果修正及多轮上下文管理，支持复杂问题的分步分析与回答。

- **RAG 与模型服务：**  
  使用 LlamaIndex、Milvus、BGE 搭建本地知识库，融合 BM25 与向量相似度实现混合检索，面向万条级信息完成知识召回；接入 Serper Search API，结合 Query Expansion 与关键词拆解扩展外部信息来源。

- **模型适配：**  
  使用 LLaMA-Factory 对 Qwen3 进行 LoRA 微调，使模型输出更贴近销售领域的术语和表达场景。

---

## 项目经历

### 阿里云 Qoder 2026 世界杯预测 Agent

**个人项目 · 一等奖**

- **端到端交付：**  
  独立构建 `DataForAgent → worldcup_agent → data → frontend` 数据链路，覆盖数据读取、Agent 推理、预测快照、质量检查与前端展示。

- **Agent 与协议数据：**  
  搭建多 Agent 推理管线，支持球队强度评估、冠军概率校准、推理解释与结构化结果输出，为前端提供可追溯的数据和运行快照。

- **React 前端：**  
  使用 Next.js、TypeScript 开发预测看板，完成首页总览、赛程树、冠军路径、球队视图、数据链路、Agent 结果及快照对比等页面。

---

### EduAgent · 多学科智能教研与学情分析平台

**个人项目 · 持续开发**

- **多智能体教研编排：**  
  面向 K12 教师设计规划、检索、数据分析、代码处理、内容写作与质量审核等 Agent；通过结构化 `ResearchState` 共享大纲、事实、图表及审核意见，以可配置迭代上限控制补充检索与内容修订。

- **教育知识库与引用溯源：**  
  围绕课程标准、教材、教案和题库构建文档解析、重叠切片、批量 Embedding 与 Milvus 向量召回链路，采用 `COSINE + IVF_FLAT` 检索，并记录来源、可信度和关联章节。

- **学情分析与长任务交互：**  
  基于 Text-to-SQL 将学情问题转换为 PostgreSQL 只读查询，拦截写操作、多语句及注释；结合 ECharts 展示趋势，通过 `asyncio Queue + SSE` 推送研究过程，并以 PostgreSQL 检查点支持取消与恢复。

- **MinerU 适配性优化：**  
  针对语文教材中古诗双栏、注释混排等复杂版式的文本漏提取问题，搭建覆盖 16 个典型页面的 MinerU 分层评测体系，配置 ONNX 与 VLM 模型，通过锚点召回、阅读顺序、文本相似度与人工复核对多档解析策略进行量化选型。

  关键文本召回率由 Flash 模式的 **92.06% 提升至 100%**，顺序正确页比例由 **75% 提升至 100%**；同时对输出结果进行再次清洗，去除由拼音带来的乱码，为后续 RAG 知识库构建提供高质量文本输入。

---

## 竞赛与荣誉

- 中国大学生计算机设计大赛（浙江省）一等奖
- 阿里云宜搭低代码大学生技术公益实践计划第一名
- 浙江省第十八届“挑战杯”金奖
- 优秀毕业生
- 浙江省政府奖学金
