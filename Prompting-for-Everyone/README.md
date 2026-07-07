# AI Prompting for Everyone (AI 提示工程 for 所有人)

> Andrew Ng (吴恩达) @ DeepLearning.AI 出品 | 面向所有人的 AI Prompt 工程入门课程 | 笔记基于课程视频 transcript 整理

---

## 📝 内容

- **课程笔记**：18 个课时 × 结构化笔记，每个笔记包含 Prompt 示例、核心原理、实践速查模板
- **原始资料**：DeepLearning.AI 官网视频课程，含 transcript、Lab 代码、Quiz — [课程链接](https://learn.deeplearning.ai/courses/ai-prompting-for-everyone)

---

<details open>
<summary><h2>🧭 课程导航</h2></summary>

### Module 1: Finding Information（信息获取）

#### [01 AI 新手与 AI 高手](./01_AI_Novice_Power_User.md)
- **关键词**：
  - 新手 vs 高手的 4 组思维对比
  - 给上下文 vs 一句话 prompt
  - AI 谄媚（Sycophancy）初步
  - 迭代式写作 vs 一步成稿

#### [02 预训练知识](./02_Pretrained_Knowledge.md)
- **关键词**：
  - 训练数据来源（数万亿词互联网文本）
  - 频率效应：热门话题 vs 冷门话题
  - AI 三大知识盲区（私有数据、过时信息、错误信息）
  - 知识截止日期（Knowledge Cutoff）

#### [03 网络搜索](./03_Web_Search.md)
- **关键词**：
  - 知识截止日期与实时信息
  - 什么需要搜索 vs 什么不需要
  - 触发搜索的两种方式
  - 搜索结果的可靠性问题

#### [04 网页搜索来源](./04_Web_Search_Sources.md)
- **关键词**：
  - AI 搜索的双层模型架构（摘要的摘要）
  - 来源质量陷阱（Reddit > 科学论文）
  - AI 搜索 vs 传统搜索引擎的适用场景
  - 在 prompt 中指定来源类型

#### [05 使用深度研究](./05_Using_Deep_Research.md)
- **关键词**：
  - Agentic AI：AI 自主规划研究路径
  - 三种信息获取模式对比（预训练/搜索/深度研究）
  - 并行搜索机制
  - 研究计划审核

---

### Module 2: AI as a Thought Partner（AI 作为思想伙伴）

#### [06 用 AI 头脑风暴](./06_Brainstorming_with_AI.md)
- **关键词**：
  - 概率分布视角：为什么 AI 默认输出平庸创意
  - 特异性上下文驱动创意（蹦床 + 猫 → 猫触发微型健身）
  - 债务还款案例：迭代反馈的力量
  - 头脑风暴 5 步标准配方

#### [07 上下文](./07_Context.md)
- **关键词**：
  - AI 上下文窗口（数十万词 vs 人类 7 件事）
  - 长文档分析：数百页合同一次上传
  - `read everything` + `think really hard` 模式
  - 最重要信息放开头或结尾

#### [08 AI 桌面应用](./08_AI_Desktop_Apps.md)
- **关键词**：
  - AI 桌面应用 vs 聊天界面的差异
  - 自主文件浏览与执行
  - 安全三原则（最小权限、审核每步、注意删除风险）
  - 提案→审核→批准→执行 工作流

#### [09 用 AI 推理](./09_Reasoning_with_AI.md)
- **关键词**：
  - 「think step-by-step」已过时 →「think hard」
  - METR 研究：AI 能力从秒级到小时级的跃迁
  - AI 推理循环（推理→发现缺口→获取信息→继续推理）
  - `ultrathink` 关键词

#### [10 AI 的谄媚问题](./10_Sycophancy.md)
- **关键词**：
  - RLHF 训练如何制造谄媚
  - Washington Post 研究：赞同倾向是反驳的 10 倍
  - 微妙的谄媚：prompt 预设答案方向
  - 中立提问法：不暴露你的立场

#### [11 用 AI 写作](./11_Writing_with_AI.md)
- **关键词**：
  - AI Slop 的识别信号（长破折号、空洞金句、三元素列表）
  - 渐进式大纲法（Progressive Outlining）
  - 大纲编辑 = 高杠杆操作
  - 写作占 ChatGPT 使用的 24%

#### [12 用 AI 审阅](./12_AI_Critique.md)
- **关键词**：
  - 逐段编辑：一次只攻一段
  - 评分量规（Rubric）破解审阅谄媚
  - 二元标准 + 逐项打分 + 最后汇总
  - 跨模型审核 + 锯齿智能（Jagged Intelligence）

---

### Module 3: Working with Multimedia & Code（多媒体与代码）

#### [13 处理多媒体数据](./13_Multimedia_Data.md)
- **关键词**：
  - 多模态 AI 能力全景（图像、语音、视频、代码）
  - 成本/速度谱系：Text < Speech < Images <<< Video
  - 语音克隆的双刃剑
  - 2022→现在的技术跨越

#### [14 图像理解](./14_Image_Understanding.md)
- **关键词**：
  - AI 视觉是「粗粒度」的
  - 成功场景：场景识别、文字提取、多图总结
  - 翻车场景：相似物体区分、细节识别
  - 图片 = 最快给上下文的捷径

#### [15 图像生成](./15_Image_Generation.md)
- **关键词**：
  - 让文字 AI 帮你写图像 prompt
  - 视觉艺术词汇 = 图像生成的编程语言
  - 扩散模型工作原理（从噪声中逐步去噪）
  - 三种常见翻车：手、文字、角色不一致

#### [16 构建应用](./16_Building_Apps.md)
- **关键词**：
  - 非程序员也能构建可玩的应用
  - Prompt 三要素：目标 × 输入 × 输出
  - 容易 vs 难构建的直觉培养
  - 番茄钟、计算器、穿搭建议器等练手项目

#### [17 数据分析](./17_Data_Analysis.md)
- **关键词**：
  - AI 自动写 Python → 执行 → 解读结果
  - 奶茶店销售分析实战案例
  - `analyze the data carefully for insights` 触发深度分析
  - 信任代码计算，质疑 AI 的文字解读

#### [18 结语](./18_Conclusion.md)
- **关键词**：
  - 从新手到高手的旅程总结
  - 三个最终建议：保持迭代、保持尝试、保持负责
  - 你现在可以做的事

</details>

---

<details>
<summary><h2>📚 资源链接</h2></summary>

| 资源 | 链接 |
|------|------|
| **课程官网** | [DeepLearning.AI — AI Prompting for Everyone](https://learn.deeplearning.ai/courses/ai-prompting-for-everyone) |
| **DeepLearning.AI 论坛** | [Discuss](https://community.deeplearning.ai/) |
| **Andrew Ng 推荐进阶课程** | [Build with Andrew](https://www.deeplearning.ai/) |

</details>

---

## 🎯 这个课程和 Anthropic Prompt Engineering Tutorial 的区别

| | Anthropic 课程 | Andrew Ng 课程 |
|------|--------------|-------------|
| **定位** | 面向 API 开发者，技术深度高 | 面向所有人，强调实用思维 |
| **内容** | 9 章：提示结构、角色、XML、格式化、思考链、示例、防幻觉、复杂提示 | 18 课：信息获取、思想伙伴、多媒体代码 |
| **风格** | 技术文档式，大量 prompt 模板 | 场景驱动，大量 Andrew Ng 个人案例 |
| **互补性** | 教你**怎么写**复杂 prompt | 教你**什么时候用什么** prompt 策略 |
