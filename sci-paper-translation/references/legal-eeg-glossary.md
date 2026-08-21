# 法律事理图谱论文固定术语

翻译当前法律人工智能与事理图谱论文时采用下列固定译法。除非用户明确修改，不要为避免重复而更换同义词。

| 中文术语 | 固定英文译法 |
|---|---|
| 事理图谱 | Event Evolutionary Graph (EEG) |
| 民事判决书 | civil judgment / civil judgments |
| 司法推理 | judicial reasoning |
| 法律事件 | legal event |
| 法律事件要素 | legal event elements |
| 标准化事件单元 | standardized event unit |
| 事件触发词 | event trigger |
| 事件论元 | event argument |
| 触发词抽取 | trigger extraction |
| 论元抽取 | argument extraction |
| 段落类型嵌入 | paragraph-type embedding |
| 段落先验知识 | prior knowledge of paragraph types |
| 深度特征融合 | deep feature fusion |
| 结构感知的语义表征 | structure-aware semantic representation |
| 双路径并行架构 | dual-path parallel architecture |
| 触发词引导的交叉注意力 | trigger-guided cross-attention |
| 长距离依赖 | long-range dependency |
| 级联误差 | cascading error |
| 序列标注 | sequence labeling |
| 一致性校验 | consistency verification / consistency validation，按图中标签选择并统一 |
| 法律本体约束矩阵 | legal ontology constraint matrix |
| 事件因果关系抽取 | event causal relation extraction |
| 事实因果关系 | factual causal relation |
| 规范因果关系 | normative causal relation |
| 因果链 | causal chain |
| 初始因果有向图 | initial directed causal graph |
| 多智能体辩论 | multi-agent debate |
| 法律领域大语言模型 | legal-domain large language model |
| 检索增强生成 | retrieval-augmented generation (RAG) |
| 法律要件 | legal elements |
| 诉讼请求基础 | basis of claim |
| 有向无环图 | directed acyclic graph (DAG) |
| 断环算法 | cycle-breaking algorithm |
| 可解释的司法辅助应用 | interpretable judicial decision-support application |
| 正方智能体 | proponent agent (ProAgent) |
| 反方智能体 | opponent agent (ConAgent) |
| 裁判智能体 | referee agent (RefAgent), which serves as the adjudicator |

## 图3固定标签

- `Deep Semantic Feature Encoding`
- `Trigger_path`
- `Argument path`
- `Boundary Recognition CRF`
- `Event Type Classification CRF`
- `Argument Extraction CRF`
- `Joint Decoding CRF`
- `Similarity Verification`
- `Cosine Similarity`
- `Euclidean Distance`
- `Invalid-pair Filtering`

## 民事判决书段落类型

- 原告诉称：`Plaintiff's claim`
- 被告辩称：`Defendant's defense`
- 法院查明：`Court findings`
- 法院认为：`Court reasoning`
- 判决结果：`Judgment result`

## 一致性规则

- 首次出现全称与缩写，后文使用缩写。
- `RefAgent` 的全称使用 `referee agent`；说明其功能时补充 `serves as the adjudicator`。
- `Event Evolutionary Graph` 不得替换为 `event knowledge graph` 或 `event logic graph`。
- `judicial reasoning` 不与 `adjudicative logic` 随意混用；只有原文明确指“裁判逻辑”时才使用后者。
- `event trigger` 不随意改为 `trigger word`；`event argument` 不随意改为 `event element`。
- 图中文字固定时，正文可以给出更完整的解释，但必须明确与图中标签的对应关系。
