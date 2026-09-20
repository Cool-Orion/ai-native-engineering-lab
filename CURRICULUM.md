# AI-Native Learning Curriculum｜人工智能原生学习路线

版本：v0.1

## 目标

把学习过程变成一个可持续更新的工程系统，而不是固定课程清单。路线会根据最新的人工智能能力、工具变化、真实项目反馈和能力证据持续调整。

## 学习原则

1. **Evidence over feeling｜证据优先于感觉**：不因为“听懂了”就算掌握，必须有可检查的实践证据。
2. **Agent-first execution｜智能体优先执行**：可以安全交给 Coding Agent（代码智能体）的机械执行不作为主要训练目标。
3. **Human judgment｜人类判断力**：重点训练 Problem Framing（问题定义）、Specification（规格说明）、Review（审查）、Evaluation（评估）和 Architecture（系统架构）。
4. **Learn on demand｜按需学习**：Python（Python 编程语言）、Git（版本控制系统）等基础知识在真实任务中学习，不先脱离实践刷完整套课程。
5. **Version the curriculum｜课程版本化**：路线变化通过 Issue（任务议题）和 Pull Request / PR（拉取请求）留下原因与证据。

## Phase 0｜GitHub 工作流基础

状态：**已完成第一轮验证**

核心能力：
- Issue（任务议题）
- Branch（分支）
- Commit（提交）
- Pull Request / PR（拉取请求）
- Review（审查）
- Merge（合并）

完成证据：已完成一次完整的 Issue → Branch → Commit → PR → Review → Merge → Close Issue（关闭任务议题）流程。

## Phase 1｜Coding Agent 与结果验证

目标：从“自己执行”转向“定义任务并验证智能体结果”。

学习内容：
- Coding Agent（代码智能体）的基本工作循环
- 阅读 Agent（智能体）的修改说明
- Diff Reading（代码差异阅读）
- 基础 Code Reading（代码阅读）
- Test Evidence（测试证据）
- Acceptance Criteria（验收标准）
- 识别“测试通过但产品做错”的情况

当前任务：Learning Goals CLI（学习目标命令行程序）实验。

## Phase 2｜Specification Engineering 与代码理解

目标：能把模糊想法变成智能体可执行、可验证的任务。

学习内容：
- Problem Framing（问题定义）
- Specification Engineering（规格工程）
- Requirements（需求）
- Constraints（约束）
- Interfaces（接口）
- Edge Cases（边界情况）
- Acceptance Criteria（验收标准）
- Python Reading（Python 代码阅读）
- Debugging（调试）基础

## Phase 3｜Testing & Evaluation｜测试与评估

目标：判断人工智能系统是否真的有效，而不是只看是否能运行。

学习内容：
- Unit Test（单元测试）
- Integration Test（集成测试）
- Regression Test（回归测试）
- Evaluation / Eval（评估）
- Benchmark（基准测试）
- Ground Truth（真实基准）
- LLM-as-a-Judge（大型语言模型作为评判者）
- Failure Analysis（失败分析）
- Calibration（校准）与 Reliability（可靠性）

## Phase 4｜Context Engineering 与 MCP

目标：让 Agent（智能体）获得正确上下文并连接真实工具和数据。

学习内容：
- Context Engineering（上下文工程）
- Project Instructions（项目规则）
- Memory（记忆）
- Skills（技能）
- Tools（工具）
- MCP / Model Context Protocol（模型上下文协议）
- MCP Server（模型上下文协议服务器）
- MCP Client（模型上下文协议客户端）
- 权限、数据边界与安全

## Phase 5｜Agent Orchestration｜智能体编排

目标：从使用一个 Agent（智能体）升级到设计智能体协作系统。

学习内容：
- Sub-agents（子智能体）
- Handoffs（任务交接）
- Parallel Agents（并行智能体）
- Role Design（角色设计）
- Human-in-the-loop（人在回路）
- Permissions（权限）
- Sandbox（沙箱）
- Observability（可观测性）

## Phase 6｜System Architecture 与真实项目

目标：能设计并交付复杂的人工智能原生系统。

学习内容：
- System Architecture（系统架构）
- Data Flow（数据流）
- API / Application Programming Interface（应用程序编程接口）
- RAG / Retrieval-Augmented Generation（检索增强生成）
- Database（数据库）
- Reliability（可靠性）
- Latency（延迟）
- Cost（成本）
- Security（安全）
- Production（生产环境）

最终要求：通过真实项目证明能力，而不是以课程完成数量作为主要成果。

## 路线更新规则

出现以下情况时更新本文件：
- 主流 Agent（智能体）能力发生明显变化；
- OpenAI、Anthropic、GitHub 等官方工作流出现重要更新；
- 当前学习顺序被实践证明低效；
- 新能力变成明显的高杠杆能力；
- 真实项目暴露出新的能力缺口。

每次重大更新应通过 Issue（任务议题）说明原因，并通过 Pull Request / PR（拉取请求）修改本文件。
