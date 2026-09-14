# Elon Musk 5-Step Algorithm · 五步工作法 Skill

> "The best part is no part. The best process is no process."
> 最好的零件是没有零件,最好的流程是没有流程。

一个 Agent Skill(OpenCode / HyperCode / Claude Code / Cursor 兼容),把 Elon Musk 的工程算法固化成可执行的评审清单,并补上未知领域模式、研发/实验运行原则、RSI 闭环与停止条件。

**四层结构:** 怎么决策(五步) → 怎么保持推进(运行原则) → 怎么确认改进是真的(RSI 闭环) → 什么时候停(锚在目标上)。

## 文件结构

```
SKILL.md                     核心:铁律 + 入口 + 第 -1 → 5 步          (每次加载)
references/operations.md     运行原则 / RSI 闭环 / 什么时候停 / 记录模板  (按需)
references/appendix.md       附加规则 / 边界 / 24 条反模式              (按需)
README.md
LICENSE                      MIT
```

`SKILL.md` 只放每次都要用的核心 + 一张入口表 + 指向 `references/` 的路标。细节按需读取,不占上下文。

## 入口:先看你手上是什么场景

| 你要干的 | 进哪 |
|---|---|
| 从零开始,连问题是什么都不知道 | `SKILL.md` · 第 -1 步 |
| 评审一个方案 / 功能 / 流程 | `SKILL.md` · 第 0 → 5 步 |
| 跑研发、跑实验、保持推进 | `references/operations.md` · 运行原则 |
| 改进了一个东西,想确认是不是真的 | `references/operations.md` · RSI 闭环 |
| 想知道什么时候收工 / 该不该放弃 | `references/operations.md` · 什么时候停 |
| 查附加规则 / 边界 / 反模式 | `references/appendix.md` |

## 七步(顺序不可颠倒)

| # | 步骤 | 一句话 |
|---|---|---|
| -1 | 参照系 | **未知领域专用。** 凭什么你认为是对的?是你在设限制,还是"常见路径"在替你设? |
| 0 | 钉住目标 | 先回答"我在往哪造",钉住**可测指标**和**预算**(时间/成本/轮次) |
| 1 | 质疑每一项要求 | 所有要求都可能是错的,尤其是聪明人提的;每条要求必须署人名 |
| 2 | 删除 | 删到你会把 10% 加回来,才算删够 —— **但先分清可逆 / 不可逆** |
| 3 | 简化 / 优化 | 只在前两步之后做;别优化一个该删的东西 |
| 4 | 加快循环时间 | 只在前三步之后做;别在坑里加速 |
| 5 | 自动化 | 最后一步;别自动化一个该删的流程 |

> 大多数人的错误是一上来就优化、加速、自动化。
> Musk 自己承认:"造 Model 3 时,我真的是先自动化、再加速、再简化,最后才删除。"

## 三层运行机制(在 `references/operations.md`)

### 研发 / 实验运行原则 · 让设备一直跑

**核心:永远有东西在跑。** 设备不空转;一个方向不行就换方向,不要停;卡住时三选一 —— **换方向 / 定位问题 / 修了再试**,但别选"等着"。失败必须变成下一轮的输入。

### RSI 闭环 · 让改进本身可验证

```
提议 → 评估(冻结评估器) → 晋升门 → 保留 / 回滚 → 记录血缘 → 下一代
```

七条硬规则:评估器不可改、留出集必须封存、没进晋升门不算改进、被拒的必须回滚、每代记血缘、失败留下残渣喂下一轮、建与审分离。

### 什么时候停

判据只有一条:**任务目标**。

| # | 条件 | 动作 |
|---|---|---|
| 1 | 目标达成 | **停**,收工 |
| 2 | 目标被证伪 / 不再成立 | **停**,回第 0 步重立目标 |
| 3 | 代价超过目标价值 | **停**,或降级目标(靠预算闸判定) |

**不算停止理由的:** "删得差不多了" / "跑腻了、没灵感" (这是换方向) / "这个方向失败了" (这是换路)。
**预算闸:** 到线强制复盘 `继续 / 换路 / 停`,**默认是停**。

## 删除的刹车

第 2 步的"疯狂删除"只在**可逆**时成立:

| 删什么 | 可逆? | 规则 |
|---|---|---|
| 代码、流程步骤、字段、会议、文档 | ✅ | **疯狂删**,按 10% 规则 |
| 数据、客户、对外承诺、已发布的 API、合规流程、钱 | ❌ | **不能按 10% 规则删** —— 先建回滚方案 + 明确批准人 |

判据:**删掉之后,你能把它完整加回来吗?**

## 用法

**作为 Skill 加载**:把整个文件夹放进你的 skills 目录:

```bash
# OpenCode / HyperCode
cp -r . ~/.config/hypercode/skills/elon-musk-5-step/

# Claude Code
cp -r . ~/.claude/skills/elon-musk-5-step/
```

**作为评审清单**:打开 `SKILL.md`,按「入口」表选层,再逐条走。任何一步答不上,就停在那一步。

## 来源

- Walter Isaacson,《Elon Musk》(2023)—— 传记中完整记录了这套"algorithm"的 5 步原文
- Elon Musk × Everyday Astronaut,Starbase 工厂访谈(2021)—— 首次完整口述五步
- Jon McNeill(前特斯拉总裁),《The Algorithm》(2026)—— 扩展到组织层面
- Mars Society 对话(2020)—— 第 0 步"目标"的来源
- 第一性原理(first principles)—— 第 -1 步"参照系"的理论底座
- RSI(Recursive Self-Improvement)社区实践 —— 内核为各家共识:`propose → evaluate(frozen) → gate → keep/rollback → record lineage → next generation`,含 kill-switch 与预算闸。参考实现:RSIHub、Darwin Gödel Machine、OpenRSI、sentrux 等

原文常见表述:
> Make the requirements less dumb → Delete the part or process → Simplify or optimize → Accelerate cycle time → Automate.

## License

MIT
