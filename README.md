# AI Workflow Playbook

一个记录 AI 如何进入真实项目流程的仓库。

这里主要整理这些内容：

- 需求收敛
- PRD 撰写
- 版本规划
- 测试准备
- 上线准备
- AI 工具组合

目标不是堆工具，也不是收集零散 prompt，而是沉淀可复用的工作流、模板、案例和小型脚本。

## 适合谁看

这个仓库更适合这些人：

- 产品经理
- 项目负责人
- 小团队
- 需要把想法变成可交付结果的人

如果你已经在用 AI，但仍然经常遇到这些问题：

- AI 输出不能直接用
- 工具很多，但流程很乱
- 需求不清楚，文档越写越散
- 测试、上线前准备总是缺东西

那这里的内容可能对你有帮助。

## 仓库结构

```text
ai-workflow-playbook/
├── README.md
├── 00-start-here/
│   ├── who-this-is-for.md
│   └── how-to-use-this-repo.md
├── 01-tool-combos/
│   ├── overview.md
│   ├── task-routing.md
│   └── cost-vs-output.md
├── 02-real-workflows/
│   ├── demand-clarification.md
│   ├── prd-drafting.md
│   ├── release-planning.md
│   ├── test-data-generation.md
│   └── launch-preparation.md
├── 03-templates/
│   ├── demand-clarification-template.md
│   ├── prd-template.md
│   ├── release-plan-template.md
│   └── launch-checklist-template.md
├── 04-cases/
│   ├── vague-demand-to-prd.md
│   ├── why-ai-prd-still-needs-editing.md
│   └── rebuilding-schedule-with-ai.md
├── 05-demos/
│   ├── test-data-generator/
│   └── doc-cleanup-script/
└── 99-assets/
    └── images/
```

## 怎么使用

如果你是第一次看，建议按这个顺序：

1. `01-tool-combos/overview.md`
2. `02-real-workflows/demand-clarification.md`
3. `03-templates/prd-template.md`

如果你更想看方法和流程，优先看：

- `02-real-workflows/`
- `04-cases/`

如果你更想直接拿来用，优先看：

- `03-templates/`
- `05-demos/`

## 更新原则

这个仓库会尽量保持简单和可复用。

更新时遵循这几个原则：

- 先在真实工作中验证，再整理进仓库
- 以 Markdown 为主，代码为辅
- 优先沉淀工作流、模板、清单和案例
- 小脚本只有在确实能解决问题时才加入

## License

MIT
