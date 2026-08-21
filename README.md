# SCI Paper Translation Skills

本仓库提供两个可独立安装的中文论文中英翻译技能。两者都把技术英语论文中的高频问题整理成可执行流程，使调用者无需再次阅读原始 PDF，也能完成语义保真、句法重组和投稿前审校。

## 版本选择

| 技能 | 适用范围 | 法律人工智能术语表 |
|---|---|---|
| [`sci-paper-translation`](sci-paper-translation/) | 各学科SCI论文的通用中译英、英文润色与语言审校 | 不包含 |
| [`legal-ai-paper-translation`](legal-ai-paper-translation/) | 法律人工智能、民事判决书、事件抽取和事理图谱论文 | 包含 |

普通论文默认使用通用版。只有任务明确涉及法律人工智能、民事判决书、法律事件或事理图谱时，才使用法律人工智能专用版。

## 通用版

主要能力：

- 保留研究对象、方法步骤、因果关系、参数、约束和结论强度；
- 处理冠词、单复数、超长句、主旨位置、时态、语态和指代；
- 检查 `respectively`、`in this paper`、数字、公式、变量、图表及段落格式；
- 清理中式表达、冗余名词和无依据的强调词；
- 不预设任何特定学科术语。

调用示例：

```text
使用 $sci-paper-translation 翻译这段中文论文，并保持技术原义和术语一致。
```

## 法律人工智能专用版

在通用语言规则之外，额外提供：

- 法律人工智能、民事判决书、法律事件与事理图谱固定术语；
- `Event Evolutionary Graph (EEG)`、事件触发词、事件论元和因果关系等译法；
- 图3固定标签、民事判决书段落类型及术语一致性规则；
- 法律限定、算法结构、正文、图表和公式之间的双层审校。

调用示例：

```text
使用 $legal-ai-paper-translation 翻译这段法律人工智能论文，并严格统一事理图谱与法律事件术语。
```

## 安装

选择所需技能目录，将该目录作为一个完整技能安装或导入。两个技能可同时安装，它们具有不同的名称和触发范围。

目标期刊已经提供作者指南时，以期刊指南为最高格式依据。

## 目录结构

```text
sci-paper-translation/
├── SKILL.md
├── agents/openai.yaml
├── assets/icon.svg
└── references/technical-english-checklist-zh.md

legal-ai-paper-translation/
├── SKILL.md
├── agents/openai.yaml
├── assets/icon.svg
└── references/
    ├── technical-english-checklist-zh.md
    └── legal-eeg-glossary.md
```

## 规则来源与整理原则

核心检查规则提炼自 Felicia Brittman 的 *The Most Common Habits from More Than 200 English Papers Written by Graduate Chinese Engineering Students*。本仓库保存的是中文结构化总结和可执行工作流，不包含原始 PDF，也不要求使用者读取原文。

部分年代较早或依赖期刊风格的规则已改写为条件式指导。例如，图表缩写、行内公式、变量格式和段落版式均应服从目标期刊规范，不作为绝对禁令。

## License

MIT
