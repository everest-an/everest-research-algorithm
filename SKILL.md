---
name: everest-research-algorithm
description: 造东西的双模式方法。探索模式(找可能存在的新东西:物理/新材料/模型研发,证伪优先 + RSI 闭环) 与 减法模式(造已知的东西:Musk 五步,质疑→删除→简化→加速→自动化)。源自 Elon Musk 的第一性原理 + 五步算法。Use when deciding how to build or discover something: subtract mode for known targets (question requirements, delete, simplify, accelerate, automate); explore mode for unknown territory (falsification-first, hypothesis search, RSI loop with frozen evaluator/promotion gate/rollback/lineage). Triggers - 五步工作法, 马斯克, 第一性原理, 探索模式, 减法模式, 造新东西, 未知领域, 物理研发, 新材料, 模型研发, 方案评审, 流程瘦身, 该不该做, 能不能删, 要不要自动化, 什么时候停, 证伪, 冻结评估器, RSI, 递归自我改进, first principles, the algorithm, divergent, convergent, falsification, unknown territory, delete before optimize, requirements less dumb, best part is no part, recursive self-improvement.
license: MIT
---

# Everest Research Algorithm

> 造东西的两套方法:**探索**(找新东西) + **减法**(造已知的东西)。
> 源自 Elon Musk 的两件工具:**第一性原理**(怎么**想**问题) + **五步算法**(怎么**建**东西)。
> "The best part is no part." 最好的零件是没有零件。

## 先分叉:你要做的是哪一类?

**「造一个已知的东西」还是「找一个可能存在的东西」?**

| 你要干的 | 用哪套 | 去哪 |
|---|---|---|
| 目标已知(造车 / 火箭 / 产品 / 降本 / 做薄 / 做快) | **减法模式** | → `references/convergent.md` |
| 目标未知(物理 / 新材料 / 模型研发 / 找新东西) | **探索模式** | → `references/divergent.md` |
| 分不清 | **默认探索模式** | 先证伪,别急着删 |

**为什么必须分:** 减法假设答案已知、方向对,做的是**删**;探索不知道答案存不存在,做的是**搜索 + 证伪**。用错方向 = 在未知领域做减法(删掉本不该删的),或在已知领域做搜索(永远不收敛)。

---

## 共享底座(两套都要)

### 让设备一直跑
- 设备 / 算力不空转,训练别停,实验台别空。下一组在上一组出结果前就排上。
- 一个方向不行 → **换方向,不要停**。卡住不是停工理由,是换路信号。
- 失败必须变成下一轮输入。跑完没产出"下一步跑什么" = 白跑。
- **想和跑并行,不是先后。** "停下来想清楚"常是拖延的高级形式。

### 预算闸
开工钉死三样:**时间盒 / 成本上限 / 轮次上限**。到线强制复盘 `继续 / 换路 / 停`,**默认是停**。

### 停止的三个来源
**目标(达成 / 被证伪 / 代价超价值) · 不可逆风险 · 预算闸** —— 任一触发必须停。
停不停只看目标,**不看累不累**。

---

## 详细内容

| 文件 | 装什么 |
|---|---|
| `references/convergent.md` | **减法模式**:目标 → 质疑 → 删除 → 简化 → 加速 → 自动化(造已知的东西) |
| `references/divergent.md` | **探索模式**:参照系 → 证伪 → 假设 → 最小实验 → RSI → 换方向 → 止损(找新东西) |
| `references/appendix.md` | 附加规则 / 边界 / 不适用场景 / 反模式(通用·探索·减法) / 一句话记忆 |

## 一句话记忆

**减法(已知):删。探索(未知):证伪。**
改得了裁判,分数就没有意义。停不停,只看目标。
