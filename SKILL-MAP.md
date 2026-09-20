# Skill Map｜能力地图

> 规则：能力状态必须有证据支撑。状态不是自我感觉，而是当前可验证水平。

## 状态定义

- **Not Started｜未开始**：尚未系统学习或实践。
- **Learning｜学习中**：理解部分概念，正在实践。
- **Working｜可工作**：能借助 Agent（智能体）完成真实任务，并能基本判断结果。
- **Proven｜已验证**：在多个真实任务中稳定完成，并留下可复查证据。

## 当前能力

| 能力 | 状态 | 当前证据 | 下一验证点 |
|---|---|---|---|
| GitHub Workflow（GitHub 工作流） | Working｜可工作 | 已完成 Issue → Branch → Commit → PR → Review → Merge → Close Issue | 独立完成多次真实 Agent 工作流并处理异常情况 |
| Coding Agent（代码智能体） | Learning｜学习中 | 已开始把结构化 Issue 交给 Agent 执行 | 能审查 Agent 产出的代码、测试和 PR，而非只接受结果 |
| Specification Engineering（规格工程） | Learning｜学习中 | 已接触 Goal、Requirements、Tests、Acceptance Criteria | 能自己把模糊需求转成高质量规格说明 |
| Code Reading（代码阅读） | Not Started｜未开始 | 暂无 | 能解释简单 Python 代码和 Agent 生成的关键逻辑 |
| Diff Reading（代码差异阅读） | Learning｜学习中 | 已完成第一次 README PR 审查 | 能审查多文件代码修改并识别异常改动 |
| Testing（测试） | Learning｜学习中 | 已理解测试用于验证需求而非证明“一切正确” | 能判断测试覆盖是否对应需求与边界情况 |
| Evaluation（评估） | Not Started｜未开始 | 暂无 | 为一个 AI 应用建立可复现评估集与指标 |
| Context Engineering（上下文工程） | Not Started｜未开始 | 暂无 | 能设计项目上下文、规则、记忆和工具输入 |
| MCP（模型上下文协议） | Not Started｜未开始 | 暂无 | 构建一个可运行的 MCP Server（模型上下文协议服务器）并连接客户端 |
| Agent Orchestration（智能体编排） | Not Started｜未开始 | 暂无 | 设计并验证多智能体分工与任务交接 |
| System Architecture（系统架构） | Not Started｜未开始 | 暂无 | 能为真实 AI 系统做组件、接口、数据流和权衡设计 |
| AI Product Building（人工智能产品构建） | Learning｜学习中 | 有小型 AI 项目实践经验；本仓库开始建立工程证据 | 交付有真实用户/真实评估的完整 AI 产品 |

## 更新规则

只有出现新的实践证据时才提升状态；出现明显遗忘、长期未实践或新技术改变能力要求时，可以降级或重新定义能力。
