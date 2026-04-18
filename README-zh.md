# skills

[English](./README.md) | [中文](./README-zh.md)

面向编程代理的可复用 skills 仓库。

## 安装方式

```bash
npx skills add https://github.com/gtn1024/skills.git
```

## 当前 Skills

### `socratic-coding-coach`

位置：`skills/socratic-coding-coach/SKILL.md`

只安装这个 skill：

```bash
npx skills add https://github.com/gtn1024/skills.git --skill socratic-coding-coach
```

这个 skill 的目标是把真实编码任务转化为“边做边学”的引导式过程，同时不牺牲交付效率。

主要功能：

- 用简短的苏格拉底式反问，引导用户自己建立对代码的理解，而不只是接受答案。
- 在调试、读代码、异步机制、状态流、数据流、架构取舍等场景中解释背后的原理。
- 提供 `light`、`standard`、`deep` 三种教学强度，适配不同学习深度。
- 控制提问频率，在每个关键推理点最多只提一个小问题，避免把协作变成面试。
- 每次解释都会落回到实际代码修改、验证动作或可迁移的方法论。

适用场景：

- 用户希望在使用 Claude Code 或类似 coding agent 时，同时学习背后的思路和原理。
- 用户希望 AI 以“教练模式”工作，而不是纯粹代做。

典型触发词：

- `coach mode`
- `teaching mode`
- `explain the why`
- `ask me questions`
- `guide me to think`
- `边做边学`
- `教练式`
- `反问`
- `原理讲解`
