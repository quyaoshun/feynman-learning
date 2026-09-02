# Feynman Deep Learning｜费曼式深度学习

一个用于深度理解与长期记忆的 Codex Skill。它把文章、书籍章节、课程笔记、PDF、概念和研究资料，从“看过”转化为可解释、可验证、可应用、可复习的知识。

> 真正掌握一个知识，不是能够认出它，而是能够脱离原文，用简单、准确、有逻辑的语言解释它，并在新的场景中使用它。

## 它会做什么

- 提炼决定整体理解的 3–7 个核心知识；
- 建立包含前提、因果、对比、边界和应用的知识地图（Knowledge Map）；
- 用面向聪明初学者的白话完成费曼解释（Feynman Explanation）；
- 诊断概念、原理、关系、应用和边界等知识缺口（Knowledge Gaps）；
- 补充例子、类比（Analogy）、反例、限制条件和迁移场景；
- 通过主动回忆（Active Recall）与苏格拉底式追问检验理解；
- 沉淀知识卡片（Knowledge Card）、复习版和一句话记忆。

它的目标不是生成更长的摘要，而是帮助学习者做到：能够脱离材料解释知识、在变化场景中使用知识，并清楚自己哪里还不懂。

## 安装

克隆仓库到 Codex 的个人 Skills 目录：

```bash
git clone https://github.com/quyaoshun/feynman-deep-learning.git ~/.codex/skills/feynman-deep-learning
```

重新打开 Codex 后即可使用。Skill 默认允许按任务内容自动触发，也可以显式调用：

```text
$feynman-deep-learning
```

## 使用示例

```text
使用 $feynman-deep-learning 帮我深入理解这篇文章。
```

```text
用费曼方式解释这个概念，并指出我可能漏掉的前置知识。
```

```text
考考我。一次只问一个问题，根据我的回答调整难度。
```

```text
帮我复习这份材料，先别展示答案，从主动回忆开始。
```

## 输出内容

完整模式通常包含：主题概览、核心问题、知识地图（Knowledge Map）、3–7 个核心知识、理解错觉、知识缺口（Knowledge Gaps）、费曼解释（Feynman Explanation）、主动自测（Active Recall）、知识卡片（Knowledge Card）和一句话记忆。对于较小主题，Skill 会合并空洞或重复的章节，避免为了套模板而制造内容。

## 设计原则

- 理解优先于完整；
- 解释优先于摘抄；
- 问题优先于答案；
- 连接优先于孤立；
- 应用优先于记忆；
- 简单但不失真；
- 材料不足时明确承认无法确定。

## 文件结构

```text
feynman-deep-learning/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── coaching.md
    └── deliverables.md
```
