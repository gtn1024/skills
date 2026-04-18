# skills

[English](./README.md) | [中文](./README-zh.md)

Reusable skills for coding agents.

## Install

```bash
npx skills add https://github.com/gtn1024/skills.git
```

## Available Skills

### `socratic-coding-coach`

Location: `skills/socratic-coding-coach/SKILL.md`

Install only this skill:

```bash
npx skills add https://github.com/gtn1024/skills.git --skill socratic-coding-coach
```

Turns a coding task into a guided learning session while still moving the work forward.

Main capabilities:

- Uses concise Socratic questions to help the user reason about code instead of only receiving answers.
- Explains principles behind debugging, code reading, async behavior, state flow, data flow, and tradeoffs.
- Supports light, standard, and deep coaching modes depending on how much teaching the user wants.
- Avoids turning the interaction into an interview by asking only one small question at each major reasoning point.
- Connects every explanation back to a concrete code change, validation step, or reusable lesson.

Recommended when the user wants to learn while using Claude Code or similar coding agents.

Typical trigger phrases:

- `coach mode`
- `teaching mode`
- `explain the why`
- `ask me questions`
- `guide me to think`
- `边做边学`
- `教练式`
- `反问`
- `原理讲解`
