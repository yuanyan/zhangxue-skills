# zhangxue-skills

以张雪机车的精神与做事风格为指导原则的 Agent Skills 合集。适用于 GitHub Copilot、Claude、Cursor 等主流 AI 编程助手。没废话，没情怀，只有能上赛道的工具。

## Skills

| Skill | 干什么的 |
|---|---|
| [dakar-resilience-runner](./skills/dakar-resilience-runner/SKILL.md) | 达喀尔级死磕调试器。报错解不了？Bug 死磕到底，永不言弃。 |
| [extreme-lightweight-refactor](./skills/extreme-lightweight-refactor/SKILL.md) | 极致轻量化重构专家。代码太臃肿？给我拆了它，减到骨架为止。 |
| [no-bs-product-challenger](./skills/no-bs-product-challenger/SKILL.md) | 反忽悠产品质检员。PRD 里的黑话过滤掉，看看这辆车到底能不能上路。 |

## 安装

```bash
# 查看所有可用 Skills
npx skills add yuanyan/zhangxue-skills --list

# 安装全部
npx skills add yuanyan/zhangxue-skills --all

# 按需安装
npx skills add yuanyan/zhangxue-skills --skill dakar-resilience-runner
npx skills add yuanyan/zhangxue-skills --skill extreme-lightweight-refactor
npx skills add yuanyan/zhangxue-skills --skill no-bs-product-challenger

# 安装到指定 Agent
npx skills add yuanyan/zhangxue-skills --all -a claude-code -a copilot
```

## 价值观

过度设计就是耍流氓。没用的代码是在谋财害命。产品不产生真实价值就是废铁。