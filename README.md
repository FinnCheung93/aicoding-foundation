<div align="center">

## AI Coding 地基

在项目开工前，把协作原则、状态记录和治理结构先立起来。  
适合用作 AI Coding 项目的开工前初始化 Skill。

<sub>Governance · Principles · State · Handoff</sub>

<br>

<p>
  <img src="https://img.shields.io/badge/Codex-Skill-2563eb?style=flat&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Version-v1.1.2-14b8a6?style=flat&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Language-中文-f59e0b?style=flat&logo=markdown&logoColor=white" />
  <img src="https://img.shields.io/badge/Series-PM%20Workflow-7c3aed?style=flat" />
</p>

</div>

```text
AI Coding 地基用于初始化一个项目的治理舱。
它会创建原则、状态、日志、检查项和建议区，让后续 PRD、Spec 和实现工作有稳定上下文。
```

## ✨ 它能帮你做什么

- 建立项目开工前的协作规则和工作边界
- 记录项目原则、当前状态、变更日志和检查项
- 给 AI Coding 任务提供长期可读的项目上下文
- 帮助团队在进入 PRD、Spec 或实现前对齐工作方式
- 把“临时开工”变成“有结构地开始”

## 🧭 适用场景

- 新项目刚创建，还没有治理结构
- 准备开始写 PRD、Spec 或进入 AI Coding 实现
- 希望项目状态、原则和建议有固定记录位置
- 多个 AI Agent 或多人协作时，需要一个共同参照
- 想减少反复解释背景和上下文丢失

## 🧩 工作方式

这个 Skill 会把项目初始化为轻量治理结构，而不是替你写 PRD 或技术方案。

- 先确认目标项目目录
- 创建或补齐 `AGENTS.md` 与 `.foundation/`
- 写入项目原则、状态、日志和检查项
- 保留人类确认与建议记录，不替代决策

## 🚦 边界

- 不负责写 PRD、Spec、架构设计或实现计划
- 不在用户只想讨论时直接写文件
- 不覆盖已有治理内容，除非明确需要更新
- 不把项目治理变成沉重流程

## 🧭 PM 工作流系列

这一组 Skills 用来把产品想法逐步推进到 AI Coding 可执行状态：

- [AI Coding 地基](https://github.com/FinnCheung93/aicoding-foundation)：项目开工前，初始化原则、状态、日志和协作治理。
- [PM PRD 助手](https://github.com/FinnCheung93/pm-prd-copilot)：澄清、撰写、修订和审查开发可落地的 PRD。
- [AI Coding 规范文档](https://github.com/FinnCheung93/aicoding-specpilot)：基于 PRD 生成更适合 AI Coding 读取的规格文档。
- [PM 原型助手](https://github.com/FinnCheung93/finn-protopilot)：基于 PRD / Spec 生成产品走查原型和演示材料。

推荐顺序：地基 → PRD → Spec → 原型。实际使用时也可以单独调用其中任意一个 Skill。

## 📦 使用方式

把本目录作为 Codex skill 安装或放入你的 skills 目录中，由 Codex 在项目初始化任务中自动触发。

```text
SKILL.md
```

<sub>未提供开源许可证，默认保留所有权利。</sub>
