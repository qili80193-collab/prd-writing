# PRD Writing

将已有产品决策、原型、会议记录或草稿整理为清晰、可执行的产品需求文档的 AI Skill。

## 适用场景

- 根据已确认的产品决策撰写 PRD。
- 整理已有 PRD 的结构，提升可读性与规则完整性。
- 将原型、会议记录或讨论材料整理为需求，区分已确认决策、讨论方案和待确认事项。
- 审阅 PRD 是否便于评审、开发和测试。

Skill 根据读者任务和信息关系选择文档结构，不强制套用固定目录，也不将 AI 推测当作已确认的产品决策。

## 在 Codex 中安装

将本仓库克隆到本地 skills 目录（目标目录应不存在）：

```sh
git clone https://github.com/qili80193-collab/prd-writing.git ~/.codex/skills/prd-writing
```

如果已安装同名 skill，请先备份，再自行合并或替换已有文件。

## 使用示例

```text
使用 $prd-writing，把这些产品决策和原型整理成供产品、研发和测试联合评审的 PRD。保留必要规则，将未确认事项明确标注。
```

## 文件说明

- `SKILL.md`：写作原则、需求表达规则与交付前自检。
- `agents/openai.yaml`：Codex 展示信息和默认提示。
- `references/information-architecture-cases.md`：信息组织案例，供复杂需求按需参考。

参考案例中的业务口径属于原文的讨论状态，不是可直接套用的通用业务规则。
