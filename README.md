# cpp-guide

This agent skill applies [Performance by Design: A C++ Guide](references/guide.md) to native C++ work. The guide covers data layout, ownership, allocation, algorithm choice, and the cost of abstractions in hot paths.

## Install

Run one of these commands and select your agent when prompted.

**npx**

```sh
npx skills add Hi9841/cpp-guide --skill cpp-guide
```

**pnpm**

```sh
pnpm dlx skills add Hi9841/cpp-guide --skill cpp-guide
```

## Use

Ask your agent to use the skill for a specific C++ task. For example:

```text
Use $cpp-guide to review the allocation and data layout in this C++ module.
```

The skill applies only when you ask for it. [SKILL.md](SKILL.md) tells the agent to read the full guide before it starts the task.
