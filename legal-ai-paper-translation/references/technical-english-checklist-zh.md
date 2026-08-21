# SCI技术英语翻译与审校清单

本清单依据附件《The Most Common Habits from more than 200 English Papers written by Graduate Chinese Engineering Students》中的常见问题整理，并结合现代SCI写作规范进行校正。将其作为审校启发式规则，而不是替代目标期刊作者指南的绝对格式要求。

## 1. 语义完整性

- 对照中文逐项核查研究对象、动作、方法、机制、输入、输出、条件、顺序和目标。
- 不得将“翻译精简”变成删去方法阶段或实验限定。
- 不得改变修饰对象。例如，“分散分布的复杂事件单元”不能改成“分散分布的异构特征”。
- 区分语言问题与内容问题。发现正文、图示、公式或其他论文内容冲突时，单独说明，不静默修正。
- 保持结论强度。`suggest/indicate/improve` 不得擅自升级为 `prove/ensure/guarantee`。

## 2. 冠词

- 逐个检查单数可数名词是否需要 `a/an/the`、其他限定词或复数形式。
- 已明确、唯一、前文提及或被后置限定的名词通常使用 `the`。
- 首次出现且非特指的单数可数名词通常使用 `a/an`。
- 不可数名词和复数泛指名词不机械添加冠词。
- 按以下顺序判断：先确认是否为名词及是否单数可数；再检查前面是否已有指示词、物主限定词、数量词或所有格；若没有限定词，特指时用 `the`，非特指时用 `a/an`。
- `a/an` 取决于后接词的读音而非拼写：辅音音素前用 `a`，元音音素前用 `an`，包括不发音的 `h`，如 `an hour`；缩写也按实际读音判断。
- 复数可数名词若已有 `some/any/both/many/several/all`、数词、序数词、物主限定词或指示词，不再叠加冠词；无此类限定词时，再判断其是泛指还是特指。
- 特别检查 `model`、`method`、`framework`、`graph`、`matrix`、`layer`、`dataset`、`judgment` 等高频技术名词。

## 3. 超长句

- 识别含有三个以上独立动作、多个因果链或多个 `which/that/while/thereby` 的句子。
- 将主要观点和支撑观点拆成独立句；每句保留一至两个紧密相关的主题。
- 中文分号连接的“首先—随后—最后”流程通常拆成多句。
- 参数或变量列表较长时改用列表、表格或逐项定义，不写成整段单句。
- 不以词数作为唯一标准；即使不足60词，只要主旨难以识别也应拆分。

## 4. 主旨位置

- 将最重要的主语和核心动作放在句首。
- 不要连续以目的、地点、原因、条件或时间状语开头，导致主旨长期推迟。
- `Figure 3 presents ...` 通常优于 `When ..., the results are shown in Fig. 3.`
- `The model uses A to achieve B.` 通常优于 `To achieve B, A is used by the model.`
- 条件是论证重点时可以放在句首，不机械后移。

## 5. 主动语态与被动语态

- 明确执行者时，让模型、模块、算法或 `we` 作主语。
- 强调处理对象、过程或结果时使用被动语态。
- 避免同一段连续堆叠 `is used/is employed/is introduced/is designed/is applied`。
- 优先把 `is used to perform the extraction of` 改为 `extracts`。
- 不滥用 `utilize`；通常使用 `use`、`apply`、`incorporate`、`employ` 或直接主动表达。

## 6. “通过、利用、基于”的处理

- `through + 名词机制`：`through task decoupling and feature sharing`
- `by + 动名词动作`：`by incorporating confidence scores`
- `using + 工具`：`using GATv2`
- `based on + 依据/基础`：仅在确实表示依据或基础时使用。
- 检查逻辑主语，避免 `By using A, B is obtained` 产生悬垂修饰。
- 能直接写成 `A enables B`、`A extracts B` 或 `A refines B` 时，不保留中文“通过”的表面结构。

## 7. `which`、`that` 与指代

- 确保关系代词紧邻且明确指向唯一先行词。
- 一个句子中存在多个可能先行词时，重复具体名词或拆句。
- 避免用 `which` 指代前面整段复杂过程而不说明具体对象。
- 非限定性补充使用逗号加 `which`；限定范围时根据句法使用 `that/which`，并服从期刊风格。

## 8. `respectively`

- 仅在两个或多个列表需要按顺序一一对应时使用。
- 通常放在对应陈述的末尾。
- 对应关系已经明确或顺序不重要时删除。
- 无法一眼确认其对应对象时，拆句或逐项说明。
- `respective` 是形容词，表示“各自的”；`respectively` 是副词，表示两组对象按先后顺序一一对应。不要互换，也不要用二者表达普通的先后顺序。

## 9. `in this paper` 与 `in this study`

- `this study` 指研究工作；`this paper` 指呈现研究的论文文本。
- 方法和实验操作通常属于 `this study`，论文结构或文章内容可使用 `this paper`。
- 不在每段重复 `In this paper/study`。提出核心贡献或与他人工作切换时再使用。
- 可直接让模型、方法或 `we` 作主语，避免程式化前缀。

## 10. 数字与公式

- 不用阿拉伯数字或缩写开头。句首写 `Twelve ...`，不要写 `12 ...`。
- 技术数据、参数、单位和公式编号使用阿拉伯数字。
- 一般性数量可依期刊规则拼写，如 `three stages`；具体测量值保留数字。
- 用完整语法引出公式，不让公式符号替代句子必要成分。
- 行文中比较符号是否直接使用，服从期刊规范；必要时写 `is greater than`。
- 变量在正文中通常使用斜体，函数名、缩写和单位通常不斜体，以目标期刊规范为准。

## 11. 图、表与编号

- 全文统一使用 `Figure` 或 `Fig.`；若采用缩写，保持 `Fig. 2` 的空格和句点格式。
- 句首优先写 `Figure 2`；正文中是否使用 `Fig. 2` 服从期刊指南。
- `Table` 通常不缩写，除非目标期刊另有规定。
- 使用 `Figure 3 presents/shows ...`，避免 `The results are showed as Figure 3.`。
- 图题、图内标签、表格字段和正文术语必须建立一一对应关系。
- 图或图题被指定不可修改时，调整正文定义，不擅自改图。

## 12. 段落

- 每段集中发展一个主题或一条方法链。
- 新主题、新阶段或新的论证功能应另起段落。
- 避免只有一句话的悬空段落，除非期刊版式或结构确有需要。
- 方法概述可按阶段分段，但不得打断紧密的输入—处理—输出关系。
- 按期刊模板统一采用首行缩进或段间空行，不能只换行却既无缩进也无段间距，导致段落边界不清。
- 不要用一个单独缩进的句子充当下一段的引子；若它与下一段属于同一主题，应合并，若承担独立论证功能，则完整发展该段。

## 13. `such as`、`etc.` 与列举

- `such as` 已表示列举不完全，不与 `etc.` 同时使用。
- 完整列举使用冒号，不使用 `such as`。
- 避免 `and etc.`。
- 例子只在有助于区分技术概念时保留；不能因删例子而丢失限定含义。

## 14. 冗余与中式表达

- 删除无增量信息的名词堆叠。优先按语境从下表选择一个核心词，不机械保留两个近义成分：

| 避免机械使用 | 通常改为其一 |
|---|---|
| `research work` | `research` / `work` |
| `limit condition` | `limit` / `condition` |
| `knowledge memory` | `knowledge` / `memory` |
| `sketch map` | `sketch` / `map` |
| `layout scheme` | `layout` / `scheme` |
| `arrangement plan` | `arrangement` / `plan` |
| `output performance` | `output` / `performance` |
| `simulation results` | `simulation` / `results` |
| `knowledge information` | `knowledge` / `information` |
| `calculation results` | `calculation` / `results` |
| `application results` | `application` / `results` |

- 是否冗余取决于语义；若两个词分别承担明确的技术含义，不得仅因出现在表中就删除其中一个。
- 检查 `different/various/数词` 后的可数名词复数。
- `literature`、`equipment`、`staff` 等词不要机械加复数词尾；根据具体语义判断。
- 不写 `by this way`；使用 `by doing this` 或 `using this method`。
- 不以 `How to ...` 直接充当陈述句主语；改用 `Determining how to ...` 或直接名词化。
- 避免无依据的 `obviously`、`clearly`、`undoubtedly`。
- 避免国际论文中的模糊地域词，如 `at home`、`abroad`、`our country`；明确写国家或地区。
- 减少 `that is to say`、`namely` 以及句尾口语化 `too`。

## 15. 最终逐句检查

对每句依次确认：

1. 谁执行动作？主语是否清楚？
2. 动作和对象是否准确？
3. 修饰语指向谁？
4. 是否遗漏中文原义或新增方法内容？
5. 是否可用更直接的动词替代名词化结构？
6. 是否包含过多独立观点？
7. 时态和语态是否符合该段功能？
8. 冠词、单复数和限定词是否正确？
9. 术语是否与前文、图表和公式一致？
10. 是否满足目标期刊格式？
