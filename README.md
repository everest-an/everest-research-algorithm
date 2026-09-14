# ElonMusk 5 step Skill

Elon Musk 五步工作法(The Algorithm)的 Agent Skill 封装 —— 用于研发、方案、流程的评审与瘦身。

## 五步

| # | 步骤 | 一句话 |
|---|---|---|
| 1 | 质疑每一项要求 | 所有要求都可能是错的,尤其是聪明人提的;每条要求必须署人名 |
| 2 | 删除 | 删到你会把 10% 加回来,才算删够 |
| 3 | 简化 / 优化 | 只在前两步之后做;别优化一个该删的东西 |
| 4 | 加快循环时间 | 只在前三步之后做;别在坑里加速 |
| 5 | 自动化 | 最后一步;别自动化一个该删的流程 |

> 顺序不可颠倒。大多数人的错误是一上来就优化、加速、自动化。

## 文件

- `SKILL.md` —— 技能本体(HyperCode / Claude Skill 格式,带 frontmatter)

## 怎么用

**作为 Skill 使用**:把整个文件夹放进 skills 目录即可被自动加载:

```
C:\Users\ASUS\.config\hypercode\skills\elon-musk-5-step\
```

**作为评审清单使用**:直接打开 `SKILL.md`,对每个待评审对象逐条走 5 步。

## 来源

Elon Musk 在多次访谈(Starship / Tesla 产线)中口述的工程算法,常见表述:
"Make the requirements less dumb → Delete the part or process → Simplify or optimize → Accelerate cycle time → Automate."
配套名言:"The best part is no part. The best process is no process."
