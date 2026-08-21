# SCI Paper Translation Skill

一个面向中文学术论文中译英与英文润色的结构化技能。它把技术英语论文中的高频问题整理成可执行流程，使调用者无需再次阅读原始 PDF，也能完成语义保真、术语统一、句法重组和投稿前审校。

## 主要能力

- 保留研究对象、方法步骤、因果关系、参数、约束和结论强度；
- 处理冠词、单复数、超长句、主旨位置、时态、语态和指代；
- 检查 `respectively`、`in this paper`、数字、公式、变量、图表及段落格式；
- 清理中式表达、冗余名词和无依据的强调词；
- 核对正文、图题、图内标签、表格字段和公式术语；
- 提供法律人工智能与事理图谱论文的可选固定术语表。

## 使用方法

将 [`sci-paper-translation/`](sci-paper-translation/) 目录作为一个完整技能安装或导入。调用时使用：

```text
使用 $sci-paper-translation 翻译这段中文论文，并保持技术原义和术语一致。
```

目标期刊已经提供作者指南时，以期刊指南为最高格式依据。

## 目录结构

| 路径 | 用途 |
|---|---|
| `sci-paper-translation/SKILL.md` | 翻译与审校的核心工作流 |
| `sci-paper-translation/references/technical-english-checklist-zh.md` | PDF 规则的完整中文结构化清单 |
| `sci-paper-translation/references/legal-eeg-glossary.md` | 法律人工智能与事理图谱固定术语 |
| `sci-paper-translation/agents/openai.yaml` | 技能界面与默认调用提示 |
| `sci-paper-translation/assets/icon.svg` | 技能图标 |

## 规则来源与整理原则

核心检查规则提炼自 Felicia Brittman 的 *The Most Common Habits from More Than 200 English Papers Written by Graduate Chinese Engineering Students*。本仓库保存的是中文结构化总结和可执行工作流，不包含原始 PDF，也不要求使用者读取原文。

部分年代较早或依赖期刊风格的规则已改写为条件式指导。例如，图表缩写、行内公式、变量格式和段落版式均应服从目标期刊规范，不作为绝对禁令。

## License

MIT
