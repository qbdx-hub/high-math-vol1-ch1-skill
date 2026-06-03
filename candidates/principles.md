# Principle Candidates

```yaml
- id: p01
  title: 定义域先行
  type: principle
  source_chapter: 第一节
  source_quote: "构成函数的要素是定义域及对应法则。"
  summary: "两个函数是否相同、复合是否成立、反函数是否存在，都必须先检查定义域和对应关系。"
  tags: [domain, function]

- id: p02
  title: 极限运算不能跳过存在性
  type: principle
  source_chapter: 第五节
  source_quote: "如果 lim f(x)、lim g(x) 都存在，则有相应四则运算法则。"
  summary: "四则运算法则只在各部分极限存在、分母极限非零等条件下使用。"
  tags: [limit, condition]

- id: p03
  title: 连续函数可用函数值求极限
  type: principle
  source_chapter: 第九节
  source_quote: "如果 f(x) 是初等函数，且 x0 是定义区间内的点，那么 lim f(x)=f(x0)。"
  summary: "直接代入法不是万能公式，它依赖函数在该点连续且该点属于定义区间。"
  tags: [continuity, substitution]

- id: p04
  title: 闭区间条件不可省
  type: principle
  source_chapter: 第十节
  source_quote: "如果函数在开区间内连续，或在闭区间上有间断点，那么不一定有界。"
  summary: "最值、零点、介值、一致连续等结论都需要先核查闭区间与连续性。"
  tags: [closed-interval, boundary]

- id: p05
  title: 等价无穷小只替换同类结构
  type: principle
  source_chapter: 第七节
  source_quote: "求两个无穷小之比的极限时，分子及分母都可用等价无穷小来代替。"
  summary: "等价替换优先用于乘除结构；遇到加减结构先化简、提因子或判主项。"
  tags: [equivalent-infinitesimal, limit]
```

