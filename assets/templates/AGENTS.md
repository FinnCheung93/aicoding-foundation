# AGENTS.md

本文档是 `{{PROJECT_NAME}}` 的 agent 工作入口。它只定义开工前必须遵守的入口协议、Mandatory Loop 和 Hard Rules；详细文件职责、记录路由和检查清单以 `.foundation/` 为准。

## Mandatory Loop

每轮重要工作按顺序执行：

1. **Load Foundation**：读取本文件、`.foundation/README.md`、`.foundation/PRINCIPLES.md`、`.foundation/STATE.md`；重大改动前读取 `.foundation/CHECKS.md`。
2. **Align Before Action**：明确本轮目标、边界、影响范围和验收方式；信息不足时先问最小澄清问题。
3. **Plan With Boundary**：说明会触碰哪些文件或模块、依赖哪些文件或模块、不触碰哪些文件或模块。
4. **Execute With Validation**：优先用脚本、临时目录、最小样例、局部路径或静态检查验证；不可旁路时说明风险。
5. **Verify And Repair**：自检、修复、再验证，直到达到本轮验收标准或明确阻塞。
6. **Record By Route**：按 `.foundation/README.md` 的文件职责和记忆路由，先判断信息性质，再更新对应治理文件；不要把长期原则、当前状态、历史事件和未裁决提案混写。
7. **Foundation Suggestion Scan**：重要工作结束前，主动检查治理文件是否暴露出需要演进的建议；未裁决建议写入 `.foundation/SUGGESTIONS.md`。

## Governance Hooks / 治理触发点

遇到以下时机，必须先做治理判断，再按 `.foundation/README.md` 的信息性质路由处理：

- 用户消息出现“记住 / 以后 / 不要再 / 每次 / 为什么没触发 / 同步 / 升级 / 版本 / 出问题了”等长期、流程或复盘信号。
- agent 准备修改文件前。
- agent 完成重要工作、准备最终回复前。
- 用户指出错误、遗漏、误解或重复问题后。
- `AGENTS.md` 或 `.foundation/` 治理文件被修改后。
- Skill 本体、模板、脚本或生成物能力变化后。
- 长任务、跨会话或上下文混乱前。

触发治理判断不等于机械改文件；先判断信息性质、裁决状态和影响范围，再记录、更新或提出待裁决建议。

## Hard Rules

- 不静默覆盖已有文件。发现冲突、旧结构或同名文件时，先说明影响并请求用户裁决。
- 不把未裁决的治理建议写进正式治理文件；影响不清时先进入 `.foundation/SUGGESTIONS.md` 或请求用户裁决。
- 不把 PRD、Specs、项目计划、测试矩阵或实现任务写入治理地基；这些内容应由对应流程或 skill 处理。
- `STATE.md` 只写当前接续信息，不写历史流水；完整历史写入 `LOG.md`。
- 如果用户要求使用真实 sub-agent 验收，而当前环境不可用，必须说明不可用，不能假装完成。
