# 古寒飞AI

> 年轻的小伙子哟~，快看~~，你背后有奥特曼！

这里不是一家“AI 解决方案公司”的官网。

更像是一个人在 Agent 时代里，看到哪里缺东西，就顺手把它造出来的实验室。

**Observe the world.  
Introspect the self.  
Keep humans in control.**

---

## What I am building

我对 AI Agent 最感兴趣的，不是“让 AI 多说几句话”。

而是让它真正拥有：

**感知世界、理解世界、操作世界的能力。**

同时，在 AI 开始真正修改现实的时候：

**人类仍然拥有最终授权。**

大致是这样：

```text
                   REAL WORLD
                        │
                        ▼
                  Perception
                        │
          ┌─────────────┼─────────────┐
          │             │             │
      Grafana       SearchOps     WorldSense
          │             │             │
          └─────────────┼─────────────┘
                        ▼
                     AI Agent
                        │
                    Reasoning
                        │
                        ▼
                  Proposed Action
                        │
                        ▼
                  Human Intent
                        │
                        ▼
                      Human
                        │
                   Authorization
                        │
                        ▼
                   REAL WORLD
```

还有另一条方向：

```text
Human
  │
  ▼
Introspect
  │
  ▼
Observe the self
```

因为 AI 不应该只帮助人观察服务器、日志和基础设施。

有时候，人也需要一块自己的仪表盘。

---

## Projects

| Project | What it does |
| --- | --- |
| **dsh-grafana** | 让 AI Agent 读取 Grafana、指标、Dashboard、告警和真实可观测世界 |
| **dsh-searchops** | Agent-native search / logs / investigation layer，OpenSearch-first |
| **dsh-human-intent** | 将人类授权密码学绑定到 AI 即将执行的具体 Action |
| **dsh-introspect** | Local-first self-observability，把人的事件、能量、时间和现实反馈变成可观察数据 |
| **dsh-mindmap** | Markdown-native AI Mindmap，让思考过程变成可视结构 |
| **dsh-worldsense** | 给 AI Agent 建立更通用的“读取世界”能力 |
| **dsh-fingerprint-signature** | Human Intent 之前的轻量人类确认实验 |
| **zTerm** | 面向 AI Agent 与真实基础设施操作的 Terminal 实验 |

---

## A few ideas behind these projects

### Capability ≠ Authority

AI **能够**执行一个动作，

不代表 AI **被授权**执行这个动作。

这就是 `dsh-human-intent` 想解决的问题。

```text
AI proposes.
Human authorizes.
The authorization is bound to the exact action.
```

---

### Data ≠ Evidence

真实世界的数据量永远比模型上下文大。

所以 Agent 不应该靠把所有日志、指标、Dashboard 全塞进 context 来“理解世界”。

更好的方式是：

```text
World
  ↓
Filter
  ↓
Aggregate
  ↓
Correlate
  ↓
Evidence
  ↓
LLM
```

这也是 `dsh-grafana` 和 `dsh-searchops` 的方向。

---

### Internal energy ≠ External progress

一个人感觉自己状态很好，

不一定意味着现实真的发生了变化。

所以 `dsh-introspect` 会把：

```text
MEL
Mental Energy Level
```

和：

```text
RRI
Reality Response Index
```

分开观察。

有时候：

```text
MEL 95
RRI 15
```

图已经说明了很多。

不需要 AI 再讲五百字大道理。

---

## Philosophy

我比较喜欢这样的工具：

```text
Local-first
Small
Composable
Inspectable
Human-controlled
```

不喜欢为了“AI”而把所有东西做成云服务。

也不喜欢为了“智能”而把确定性计算交给模型。

程序擅长的：

```text
计算
聚合
索引
过滤
校验
存储
```

程序来做。

模型擅长的：

```text
理解
推理
解释
组合
```

模型来做。

---

## Current direction

现在主要围绕几个问题玩：

```text
How can agents read the world?

How can agents understand large real systems?

How should humans authorize agents to change the world?

How can humans observe themselves with the same seriousness
that engineers observe production systems?
```

不知道最后会长成什么。

先造。

---

<p align="center">
  <b>Observe the world. Introspect the self. Keep humans in control.</b>
</p>
