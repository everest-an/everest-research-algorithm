# Everest Research Algorithm

> 造东西的两套方法:**探索**(找新东西) + **减法**(造已知的东西)。
> "The best part is no part." 最好的零件是没有零件。

一个 Agent Skill(OpenCode / HyperCode / Claude Code / Cursor 兼容)。把两套方法固化成可执行的检查清单:

- **探索模式**(divergent)—— 物理 / 新材料 / 模型研发等**未知领域**,证伪优先 + RSI 闭环。
- **减法模式**(convergent)—— 造已知目标,**Musk 五步**:质疑 → 删除 → 简化 → 加速 → 自动化。

## 先分叉

**「造一个已知的东西」还是「找一个可能存在的东西」?**

| 你要干的 | 用哪套 | 去哪 |
|---|---|---|
| 目标已知(造车 / 火箭 / 产品 / 降本 / 做薄) | 减法模式 | `references/convergent.md` |
| 目标未知(物理 / 新材料 / 模型研发) | 探索模式 | `references/divergent.md` |
| 分不清 | 默认探索模式 | 先证伪,别急着删 |

## 文件结构

```
SKILL.md                      入口 + 路由分叉 + 共享底座
references/convergent.md      减法模式:0 目标 → 1 质疑 → 2 删除 → 3 简化 → 4 加速 → 5 自动化
references/divergent.md       探索模式:参照系 → 证伪判据 → 并行假设 → 最小实验 → RSI → 换方向 → 止损
references/appendix.md        附加规则 / 边界 / 反模式(通用·探索·减法) / 一句话记忆
README.md
LICENSE                       MIT
```

## 共享底座(两套都要)

- **让设备一直跑** —— 设备不空转;一个方向不行就换方向,别停;失败变成下一轮输入;想和跑并行。
- **预算闸** —— 钉死时间盒 / 成本上限 / 轮次上限;到线强制复盘 `继续 / 换路 / 停`,默认停。
- **停止三来源** —— 目标(达成 / 被证伪 / 代价超价值)· 不可逆风险 · 预算闸。

## 减法模式(convergent · 造已知的东西)

源自 Musk 五步算法。铁律:**顺序不可颠倒。**

**0 目标 → 1 质疑 → 2 删除 → 3 简化 → 4 加速 → 5 自动化**

- 每条要求必须**署人名**;质疑一切,包括你自己提的。
- 删除判据:**没加回至少 10%,说明删得不够狠**。
- 可逆性分级:可逆(代码/流程)→ 疯狂删;冻结(评估器/测试/门禁)→ 不删;不可逆(数据/客户/API/钱)→ 先建回滚方案。

## 探索模式(divergent · 找新东西)

源自第一性原理 + 科学方法 + RSI。铁律:**证伪优先,别急着证明。**

**参照系 → 证伪判据 → 并行假设 → 最小实验 → RSI 闭环 → 换方向 → 止损**

- 参照系:凭什么你认为是对的?物理约束 vs 约定约束。
- 证伪判据:未知领域没有基准,先定"能判断假设死没死"的那一个观测。
- RSI 七条硬规则:评估器不可改 / 留出集封存 / 没进晋升门不算改进 / 被拒必须回滚 / 每代记血缘 / 失败留残渣喂下一轮 / 建审分离。

## 用法

**作为 Skill 加载**:把整个文件夹放进 skills 目录:

```bash
# OpenCode / HyperCode
cp -r . ~/.config/hypercode/skills/everest-research-algorithm/

# Claude Code
cp -r . ~/.claude/skills/everest-research-algorithm/
```

**作为清单使用**:打开 `SKILL.md`,先做「先分叉」,再进对应模式。

## 来源

- **减法模式** —— Elon Musk 五步算法:Walter Isaacson《Elon Musk》(2023)、Everyday Astronaut Starbase 访谈(2021)
- **探索模式** —— 第一性原理 + 科学方法(证伪)+ RSI 社区实践(RSIHub / Darwin Gödel Machine / OpenRSI / sentrux 等)
- **共享底座** —— Jon McNeill《The Algorithm》(2026)、Mars Society 对话(2020)

## License

MIT
