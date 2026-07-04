# 暑期 AI 工程实践训练营

## 课程定位

本训练营面向具备基础 Python 编程能力、希望进入 AI 工程实践和 AI 辅助 PCB 设计方向的本科生。课程采用项目驱动方式，围绕“数据处理、模型训练、大语言模型应用、RAG/Agent、PCB 工具实践、AI Coding、最终项目展示”逐步展开。

课程强调动手实践。每一周都配有独立目录和学习指南，学员应按照对应 week 目录中的文档逐步完成任务。

## 课程目标

完成训练营后，学员应具备以下能力：

- 使用 Python、VS Code、Jupyter Notebook 完成基础 AI 项目开发。
- 理解并实践机器学习项目的基本流程：数据、特征、模型、评估、可视化。
- 使用 PyTorch 理解深度学习训练流程和图像分类任务。
- 调用大语言模型 API，完成基础 LLM 应用开发。
- 构建简单的 RAG、Agent 和本地工具调用项目。
- 安装并使用 KiCad 完成基础 PCB 设计流程。
- 了解强化学习在 PCB 组件摆放中的应用方式。
- 使用 Opencode + DeepSeek 辅助完成代码生成、调试、重构和文档整理。
- 将课程项目整理为可运行、可展示、可汇报的最终成果。

## 课程目录结构

```text
ai-engineering-summer-camp/
├── week1/   # Python AI 工程基础
├── week2/   # PyTorch 深度学习实践
├── week3/   # 大语言模型应用开发
├── week4/   # Agent + RAG 开发
├── week5/   # KiCad 入门与强化学习 PCB 实践
├── week6/   # Opencode + DeepSeek AI Coding 实践
├── week7/   # 项目优化与成果展示
└── README.md
```

## 学习方式

建议每周按照下面顺序学习：

1. 先阅读该周的学习指南。
2. 再阅读该周的运行指南或动手实践步骤。
3. 按步骤完成环境配置、代码运行、实验修改和结果记录。
4. 保存每周要求的代码、截图、报告或演示材料。
5. 在进入下一周前，完成该周的自检清单或里程碑要求。

如果某一步运行失败，优先复制完整报错，再根据运行指南中的排错步骤处理。

---

# 第一周：Python AI 工程基础

## 课程主题

从 Python 开发者成长为 AI 工程师，理解 AI 项目的完整开发流程。

## 对应目录

```text
week1/
├── 1.第一周学习指南.md
├── 2.开发环境Setup.md
└── 3.第一周动手实践步骤.md
```

## 本周目标

通过房价预测线性回归项目，理解一个 AI 项目从数据读取、EDA、特征工程、模型训练到模型评估的基本流程。

## 核心内容

- Python AI 开发环境配置。
- VS Code 与 Jupyter Notebook 基本使用。
- NumPy、Pandas、Matplotlib 基础。
- Feature、Label、训练集、测试集的概念。
- 使用 scikit-learn 完成线性回归模型训练。
- 使用 MAE、RMSE、R2 等指标评估模型效果。

## 实践任务

- 按 `2.开发环境Setup.md` 完成 Python、VS Code、Jupyter 环境配置。
- 按 `3.第一周动手实践步骤.md` 完成房价预测项目。
- 完成数据读取、EDA、特征工程、模型训练、模型评估和结果可视化。

## 本周交付物

- 可运行的房价预测实验。
- 数据分析和模型训练结果。
- 图表、评估结果和学习记录。

## 学习成果

完成本周后，学员应能够说明一个基础机器学习项目的完整流程，并能独立完成一个简单线性回归项目。

---

# 第二周：PyTorch 深度学习实践

## 课程主题

从线性回归到神经网络，理解深度学习训练流程和图像分类任务。

## 对应目录

```text
week2/
├── 1.第二周学习指南.md
└── 2.参考材料-MNIST识别与神经网络MLP和cnn.md
```

## 本周目标

通过 MNIST 手写数字识别任务，理解 PyTorch 中 Tensor、Dataset、DataLoader、模型、损失函数、优化器和训练循环之间的关系。

## 核心内容

- PyTorch Tensor 基础。
- Dataset 与 DataLoader。
- MLP 神经网络结构。
- Loss、Optimizer、Epoch、Accuracy。
- CNN 的基本概念和相对 MLP 的优势。

## 实践任务

- 阅读第二周学习指南。
- 按参考材料理解 MNIST 数据加载、MLP 分类器和 CNN 基础概念。
- 完成训练流程理解、模型评估和结果分析。

## 本周交付物

- MNIST 图像分类学习记录。
- MLP 与 CNN 对比理解。
- 训练过程、准确率和错误样本分析。

## 学习成果

完成本周后，学员应能够读懂并解释一个 PyTorch 图像分类项目的核心流程。

---

# 第三周：大语言模型应用开发

## 课程主题

开发第一个 LLM 应用，理解 Prompt Engineering 和 OpenAI 兼容 API 调用方式。

## 对应目录

```text
week3/
├── 1.第三周学习指南.md
├── 2.运行指南.md
├── .env.example
├── requirements.txt
├── notebooks/
├── prompts/
├── results/
└── src/
```

## 本周目标

通过 Jupyter Notebook 形式完成一个 LLM 聊天助手实验，理解 Prompt 设计、API 调用、Mock 回退和结果记录。

## 核心内容

- Prompt Engineering 基础。
- DeepSeek/OpenAI 兼容 API 的调用方式。
- `.env` 配置和 API Key 安全管理。
- LLM 聊天助手的输入、输出和结果保存。
- 无 API Key 时的 Mock 模式。

## 实践任务

- 按 `2.运行指南.md` 配置 Python 环境和依赖。
- 从 `.env.example` 创建本地 `.env` 文件。
- 运行 `notebooks/week03_llm_chat_assistant.ipynb`。
- 完成 Prompt 设计、模型调用和结果记录。

## 本周交付物

- 可运行的 LLM Notebook。
- Prompt 示例与实验结果。
- LLM 调用记录或 Mock 运行结果。

## 学习成果

完成本周后，学员应能够独立配置 API Key，并完成一个基础 LLM 应用原型。

---

# 第四周：Agent + RAG 开发

## 课程主题

构建具有知识库检索和工具调用能力的 AI 助手。

## 对应目录

```text
week4/
├── 1.第四周学习指南.md
├── 2.运行指南.md
├── requirements.txt
├── data/docs/
├── src/
├── vector_store/
└── results/
```

## 本周目标

通过 Python 程序工程完成一个本地 RAG 与 Agent 示例，理解文档加载、切分、检索、问答和工具调用的基础流程。

## 核心内容

- 文档加载与文本切分。
- 简单向量索引与检索。
- RAG 问答流程。
- Agent 工具调用思路。
- MCP-like 本地工具调用演示。

## 实践任务

- 按 `2.运行指南.md` 安装依赖。
- 运行 `src/build_index.py` 构建索引。
- 运行 `src/rag_ask.py` 完成知识库问答。
- 运行 `src/agent_demo.py` 理解工具调用。
- 运行 `src/mcp_like_demo.py` 理解 MCP-like 调用流程。

## 本周交付物

- 构建好的 `vector_store/`。
- RAG 检索结果和问答结果。
- Agent 和 MCP-like 示例运行记录。

## 学习成果

完成本周后，学员应能够说明 RAG 系统的组成部分，并能运行一个基础的本地知识库问答项目。

---

# 第五周：KiCad 入门与强化学习 PCB 实践

## 课程主题

了解 PCB 设计流程，体验强化学习在 PCB 组件摆放中的应用。

## 对应目录

```text
week5/
├── 1.第五周学习指南.md
├── 2.运行指南.md
├── kicad_project/
├── rl_pcb_workspace/
├── gerber/
├── screenshots/
├── reports/
└── scripts/
```

## 本周目标

完成 KiCad 8.0 入门实践，绘制第一个 5V 转 3.3V 电源转换板，并尝试配置运行开源强化学习 PCB 组件摆放项目 `rl_pcb`。

## 核心内容

- KiCad 8.0 下载、安装和基础使用。
- 原理图、PCB Layout、DRC 检查和 Gerber 输出。
- 5V 转 3.3V 电源转换板设计流程。
- GitHub 开源项目 `rl_pcb` 的克隆、环境配置和 Demo 运行。
- 强化学习在 PCB 组件摆放中的基本思路。

## 实践任务

- 按 `2.运行指南.md` 安装 KiCad 8.0。
- 跟随 B 站或 YouTube 的 KiCad 入门教程完成基础操作。
- 按 `kicad_project/` 中的规格和检查表完成电源转换板。
- 导出 Gerber 文件并保存到 `gerber/`。
- 克隆并运行 `rl_pcb` Demo，记录配置过程。
- 使用 `scripts/check_week5_deliverables.py` 检查交付物。

## 本周交付物

- KiCad 工程文件。
- Gerber 文件。
- KiCad 实践报告。
- `rl_pcb` 配置和运行记录。
- Week 5 总结报告。

## 学习成果

完成本周后，学员应能够描述基础 PCB 设计流程，并初步理解强化学习 PCB 布局项目的工程结构。

---

# 第六周：Opencode + DeepSeek AI Coding 实践

## 课程主题

让 AI 成为 Pair Programmer，学习 AI Coding 的安全工作流。

## 对应目录

```text
week6/
├── 1.第六周学习指南.md
├── 2.运行指南.md
├── docs/
├── task-tracker/
├── snapshots/
└── reports/
```

## 本周目标

使用 Opencode 连接 DeepSeek，在本地完成一个 Python 命令行 Task Tracker 项目，并练习只读分析、测试优先、Bug 修复、重构、文档生成和安全边界控制。

## 核心内容

- Opencode 安装与 DeepSeek 连接。
- Python 虚拟环境和 pytest。
- AI Coding 中的只读分析与修改前计划。
- 测试优先开发。
- Bug 复现、修复和验证。
- 多文件功能开发与小范围重构。
- 使用 `AGENTS.md` 固化项目规则。

## 实践任务

- 按 `2.运行指南.md` 安装 VS Code、Python、Node.js、Opencode。
- 按 `docs/opencode_deepseek_setup.md` 连接 DeepSeek。
- 按 `docs/experiment_plan.md` 完成 10 个实验。
- 使用 `snapshots/` 保存阶段性本地快照。
- 在 `reports/` 中记录 Prompt、Bug 修复和最终报告。

## 本周交付物

- `task-tracker/` Python 命令行项目。
- pytest 测试结果。
- AI Coding Prompt 记录。
- Bug 修复记录。
- 最终报告。

## 学习成果

完成本周后，学员应能够使用 Opencode + DeepSeek 进行安全、可验证、可记录的 AI 辅助编程。

---

# 第七周：项目优化与成果展示

## 课程主题

从 Demo 到可展示项目，完成 AI 工程项目的最终交付。

## 对应目录

```text
week7/
├── 1.第七周学习指南.md
├── 2.运行指南.md
├── final_project/
├── demo/
├── docs/
├── reports/
└── slides/
```

## 本周目标

从前六周中选择一个项目，整理成可以运行、可以展示、可以汇报、可以继续迭代的最终项目。

## 核心内容

- 项目功能检查和问题修复。
- 使用 Opencode + DeepSeek 做项目体检和小范围重构。
- README、安装说明、运行说明和项目结构整理。
- Git/GitHub 工程化。
- Demo 脚本、截图、PPT 提纲和最终报告。

## 实践任务

- 按 `2.运行指南.md` 选择一个最终项目。
- 将项目复制到 `final_project/`。
- 完成第一次完整运行。
- 使用 Opencode + DeepSeek 做只读项目体检。
- 修复一个明确问题并完成一次小范围重构。
- 初始化 Git 仓库并完成至少一次提交。
- 准备 Demo 脚本、PPT 提纲和最终报告。
- 按 `docs/final_checklist.md` 完成最终验收。

## 本周交付物

- `final_project/` 最终项目。
- 项目 README 和安装运行说明。
- AI Coding 记录。
- Demo 脚本和截图。
- PPT 提纲或 PPT 文件。
- Final Report。

## 学习成果

完成本周后，学员应能够把一个练习项目整理为规范的 AI 工程交付物，并完成项目展示。

---

# 最终交付要求

训练营结束时，建议提交以下内容：

- 每周完成的代码、Notebook、脚本或工程文件。
- 每周运行结果、截图、报告或学习记录。
- Week 7 最终项目工程。
- 最终项目 README。
- 最终项目演示脚本和 PPT。
- AI Coding 关键 Prompt 与修复记录。

最终项目应做到：

- 能按文档完成环境安装。
- 能按 README 运行核心功能。
- 有明确项目结构。
- 有结果截图或运行记录。
- 有后续优化方向。

---

# 后续 AI 辅助 PCB 设计学习路线

完成本训练营后，学员已经具备 Python、AI 工程、LLM 应用、RAG/Agent、KiCad 和 AI Coding 的基础。若继续进入 AI 辅助 PCB 设计方向，可按以下路线深化。

## 阶段一：PCB 与电子工程基础

- 继续学习 KiCad 原理图、PCB Layout、Gerber、DRC、封装库和网表。
- 练习绘制单片机最小系统、电源模块、传感器接口板等小型 PCB。
- 理解走线、过孔、层叠、阻抗、去耦、电源完整性等基础概念。

## 阶段二：优化理论与 EDA 建模

- 学习连续优化、组合优化和约束优化。
- 将 PCB 摆放、布线、避障、线长约束等问题抽象为优化问题。
- 熟悉图结构、网表解析和几何约束表达。

## 阶段三：图神经网络与强化学习

- 学习 PyTorch Geometric 等图神经网络工具。
- 将电路网表建模为图，尝试节点分类、连接预测或布局质量预测。
- 学习强化学习中的 MDP、PPO、SAC 等方法。
- 在简化的 2D 栅格环境中实现组件摆放或路径规划实验。

## 阶段四：AI + EDA 工程实践

- 学习 KiCad Python API，尝试自动读取 PCB 对象和生成简单布局脚本。
- 研究开源 PCB 布局、布线和 EDA 自动化项目。
- 尝试将 LLM、RAG、Agent 与 PCB 文档、设计规则、自动脚本结合。

## 阶段五：科研与前沿方向

- 阅读 AI for EDA、PCB 自动布局、强化学习布线、GNN 电路建模相关论文。
- 关注代理模型、热仿真、电磁仿真加速、制造缺陷检测等方向。
- 选择一个具体问题做长期项目，例如 PCB 组件自动摆放、规则检查助手、KiCad 自动脚本生成或 PCB 知识库问答系统。
