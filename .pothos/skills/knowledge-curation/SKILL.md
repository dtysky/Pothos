---
name: knowledge-curation
description: 用于在新增资料、长期协作和重要结论沉淀后更新 Pothos 知识库。
---

# Knowledge Curation

## 目的

用于把后续协作中的稳定认识，沉淀回 `.pothos/knowledge/`，保持 `Pothos` 的长期记忆可用、可校验、可复用。

## 何时使用

当用户提出以下需求时使用：

- 让我继续了解新的作品、项目或人生资料
- 想把一次对话中的共识沉淀成长期记忆
- 想更新人物画像、文风规则或项目方法论

不要用本技能承接普通的单次调研报告。单次调研、行前案头研究和专题资料包应优先写入 `research/`，除非其中已经形成了长期稳定、后续会反复调用的结论。

## 更新原则

- 只写高信号、相对稳定、后续真的会用到的信息
- 结论优先，不堆原文
- 明确区分事实、推断和工作建议
- 不把一次性情绪当成人格定论

## 更新目标

- `.pothos/knowledge/profile.md`
- `.pothos/knowledge/style.md`
- `.pothos/knowledge/projects.md`
- 必要时补充 `.pothos/knowledge/index.md`

## 工作流

### Step 1

先判断新信息属于：

- 背景
- 文风
- 项目方法
- 临时波动
- 单次调研

### Step 2

只有背景、文风、项目方法这 3 类进入知识库。临时波动默认不写入；单次调研默认进入 `research/` 或对应项目的 `projects/<project-code>/research/`。

### Step 3

写入时优先采用：

- 摘要
- 规律
- 边界
- 可复用规则

### Step 4

更新后复查：

- 有没有写得过满
- 有没有武断补全
- 有没有把象征系统误写成事实
