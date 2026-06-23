# Log

本文档是重要历史账本。它记录发生过什么、何时发生、为什么重要、影响什么、结果是什么，并引用相关 artifact；它不复制长文档全文，也不替代 ADR、STATE 或项目计划。

## Entry Format

```text
时间：
类型：初始化 / 升级 / 同步 / 决策 / 变更 / 事故 / 验收 / 复盘 / 归档 / 迁移
摘要：
原因：
影响范围：
结果：
引用：
后续：
```

## Entries

### {{INIT_TIME}} - 初始化

类型：初始化  
摘要：创建 Agentic Foundation v{{FOUNDATION_VERSION}}。  
原因：为 agent 参与项目建立入口、项目地图、治理路由、长期原则、当前接手快照和重要历史账本。  
影响范围：`AGENTS.md`、`README.md`、`docs/README.md`、`docs/foundation/`。  
结果：默认地基已就绪；未创建 ADR、archive、review、hooks、open questions、coding guidance 或其它可追加模块。  
引用：无。  
后续：如需 PRD、Specs、计划、架构、QA 或实现，使用对应项目文档或专业流程。
