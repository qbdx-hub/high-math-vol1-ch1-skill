# Framework Candidates

```yaml
- id: f01
  title: 函数对象合法性诊断
  type: framework
  source_chapter: 第一节 映射与函数
  source_quote: "构成一个映射必须具备以下三个要素：集合 X、集合 Y、对应法则 f。"
  summary: |
    遇到函数、反函数、复合函数和分段函数题时，先检查对象是否定义清楚：
    定义域是什么，对应是否单值，值域是否落在后续函数允许输入中。
  tags: [function, domain, composition]

- id: f02
  title: 极限定义证明流程
  type: framework
  source_chapter: 第二节 数列的极限；第三节 函数的极限
  source_quote: "对于任意给定的正数 epsilon，总存在正整数 N..."
  summary: |
    把“趋近”翻译成 epsilon-N 或 epsilon-delta 语言，先化简目标差值，
    再反推 N 或 delta，最后写成正向证明。
  tags: [limit, proof, epsilon]

- id: f03
  title: 无穷小-极限转换
  type: framework
  source_chapter: 第四节 无穷小与无穷大
  source_quote: "函数具有极限 A 的充分必要条件是 f(x)=A+alpha，其中 alpha 是无穷小。"
  summary: |
    把极限等于 A 的问题转化为“误差项是否为无穷小”，再利用无穷小代数运算证明或计算。
  tags: [limit, infinitesimal]

- id: f04
  title: 极限计算路径选择
  type: framework
  source_chapter: 第五节 极限运算法则；第六节 两个重要极限
  source_quote: "本节讨论极限的求法，主要是建立极限的四则运算法则和复合函数的极限运算法则。"
  summary: |
    对计算型极限，先检查能否直接代入或用连续性，再检查四则运算条件，
    再考虑变形、代换、两个重要极限和复合函数极限。
  tags: [limit, computation, substitution]

- id: f05
  title: 极限存在准则选择
  type: framework
  source_chapter: 第六节 极限存在准则两个重要极限
  source_quote: "准则 II 单调有界数列必有极限。"
  summary: |
    当极限值难以直接算出时，转向存在性证明：能夹在两个同极限对象之间用夹逼，
    有单调和有界结构用单调有界准则。
  tags: [limit, existence, squeeze]

- id: f06
  title: 等价无穷小替换
  type: framework
  source_chapter: 第七节 无穷小的比较
  source_quote: "求两个无穷小之比的极限时，分子及分母都可用等价无穷小来代替。"
  summary: |
    对乘积、商中的无穷小因子，用比值为 1 的等价对象替换，以简化极限。
    同时排除在加减式中乱替换的情形。
  tags: [limit, equivalent-infinitesimal]

- id: f07
  title: 连续性与间断点诊断
  type: framework
  source_chapter: 第八节 函数的连续性与间断点
  source_quote: "如果 lim f(x)=f(x0)，那么称函数在点 x0 连续。"
  summary: |
    对点连续和间断点题，按“是否定义、极限是否存在、极限是否等于函数值、左右极限如何”逐项诊断。
  tags: [continuity, discontinuity]

- id: f08
  title: 闭区间连续定理工具箱
  type: framework
  source_chapter: 第十节 闭区间上连续函数的性质
  source_quote: "在闭区间上连续的函数在该区间上有界且一定能取得最大值和最小值。"
  summary: |
    看到闭区间连续函数，就可以考虑最值、零点、介值、一致连续等存在性工具。
    第一动作是核查闭区间和连续性。
  tags: [continuity, closed-interval, existence]
```

