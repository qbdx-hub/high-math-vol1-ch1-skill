# Counter Example Candidates

```yaml
- id: ce01
  title: 值域不等于到达集合
  type: counter-example
  source_chapter: 第一节
  source_quote: "映射 f 的值域是 Y 的一个子集。"
  summary: "把陪域当值域，会误判满射、反函数或复合函数。"
  tags: [function, range]

- id: ce02
  title: 非单射不能求反函数
  type: counter-example
  source_chapter: 第一节
  source_quote: "只有单射才存在逆映射。"
  summary: "如 y=x^2 在 R 上不是一一对应，不能直接写全局反函数。"
  tags: [inverse, one-to-one]

- id: ce03
  title: 左右极限不相等
  type: counter-example
  source_chapter: 第三节；第八节
  source_quote: "左极限与右极限虽都存在，但不相等，故极限不存在。"
  summary: "只算一侧或只看函数值会误判极限存在和连续性。"
  tags: [limit, discontinuity]

- id: ce04
  title: 有界不保证收敛
  type: counter-example
  source_chapter: 第二节；第六节
  source_quote: "有界这一条件是必要的，但不是充分条件。"
  summary: "数列极限存在性不能只看有界；若要用单调有界准则，还必须证明单调。"
  tags: [sequence, existence]

- id: ce05
  title: 等价无穷小乱用于加减
  type: counter-example
  source_chapter: 第七节
  source_quote: "求两个无穷小之比的极限时，分子及分母可用等价无穷小代替。"
  summary: "教材表述限定在比值结构；在加减结构直接替换可能改变主项抵消关系。"
  tags: [equivalent-infinitesimal, boundary]

- id: ce06
  title: 缺少闭区间或连续性时最值定理失效
  type: counter-example
  source_chapter: 第十节
  source_quote: "开区间内连续，或闭区间上有间断点，不一定有界。"
  summary: "最值、零点、介值定理的前提不是装饰条件，不能省。"
  tags: [closed-interval, continuity]
```

