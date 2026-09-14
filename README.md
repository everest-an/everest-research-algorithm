# Elon Musk 5-Step Algorithm · 五步工作法 Skill

> "The best part is no part. The best process is no process."
> 最好的零件是没有零件,最好的流程是没有流程。

一个 Agent Skill(OpenCode / HyperCode / Claude Code / Cursor 兼容),把 Elon Musk 的工程算法固化成可执行的评审清单。

## 六步(顺序不可颠倒)

| # | 步骤 | 一句话 |
|---|---|---|
| 0 | 钉住目标 | 先回答"我在往哪造",否则质疑没有基准 |
| 1 | 质疑每一项要求 | 所有要求都可能是错的,尤其是聪明人提的;每条要求必须署人名 |
| 2 | 删除 | 删到你会把 10% 加回来,才算删够 |
| 3 | 简化 / 优化 | 只在前两步之后做;别优化一个该删的东西 |
| 4 | 加快循环时间 | 只在前三步之后做;别在坑里加速 |
| 5 | 自动化 | 最后一步;别自动化一个该删的流程 |

> 大多数人的错误是一上来就优化、加速、自动化。
> Musk 自己承认:"造 Model 3 时,我真的是先自动化、再加速、再简化,最后才删除。"

## 除了五步,还包含

- **附加规则(corollaries)** —— 管理者必须动手、警惕同志情谊、"可以错别自信地错"、跳过一级、唯一的铁律是物理定律、疯狂的紧迫感。这些不是第 6 步,是让算法在团队里跑得动的前提。
- **边界** —— 五步不是五等分(价值几乎全在前两步);它是循环不是一次性流程;它不负责验证和安全兜底;它需要授权。
- **反模式表** + 一句话一格的记录模板。

## 文件

```
SKILL.md    技能本体(带 frontmatter,可直接加载)
README.md   本文件
LICENSE     MIT
```

## 用法

**作为 Skill 加载**:把文件夹放进你的 skills 目录:

```bash
# OpenCode / HyperCode
cp -r . ~/.config/hypercode/skills/elon-musk-5-step/

# Claude Code
cp -r . ~/.claude/skills/elon-musk-5-step/
```

**作为评审清单**:直接打开 `SKILL.md`,对每个待评审对象逐条走 0 → 5 步。任何一步答不上,就停在那一步。

## 来源

- Walter Isaacson,《Elon Musk》(2023)—— 传记中完整记录了这套"algorithm"的 5 步原文
- Elon Musk × Everyday Astronaut,Starbase 工厂访谈(2021)—— 首次完整口述五步
- Jon McNeill(前特斯拉总裁),《The Algorithm》(2026)—— 扩展到组织层面
- Mars Society 对话(2020)—— 第 0 步"目标"的来源

原文常见表述:
> Make the requirements less dumb → Delete the part or process → Simplify or optimize → Accelerate cycle time → Automate.

## License

MIT
