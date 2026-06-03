# Case Candidates

```yaml
- id: c01
  title: arcsin 的反函数合法性
  type: case
  source_chapter: 第一节
  source_quote: "只有单射才存在逆映射。"
  summary: "教材用 arcsin 的主值说明反函数需要先限制到单射区间。"
  bound_to: [function-mapping-diagnostics]
  tags: [inverse, domain]

- id: c02
  title: 复合函数 sqrt(tan x) 的定义域限制
  type: case
  source_chapter: 第一节
  source_quote: "复合函数的条件是函数 g 的值域必须包含于函数 f 的定义域。"
  summary: "教材用 sqrt(tan x) 说明不能只看内外函数自然定义域，必须让 tan x 落入非负区间。"
  bound_to: [function-mapping-diagnostics]
  tags: [composition, domain]

- id: c03
  title: 用定义证明数列极限
  type: case
  source_chapter: 第二节
  source_quote: "多采取这种找出一个符合定义要求的正整数 N 的方法。"
  summary: "教材在数列极限例题中示范从不等式反推出 N，再回写证明。"
  bound_to: [limit-definition-proof]
  tags: [epsilon-N, proof]

- id: c04
  title: 用夹逼准则证明 sin x / x 的极限
  type: case
  source_chapter: 第六节
  source_quote: "应用夹逼准则，即得相应极限。"
  summary: "教材通过几何面积不等式把 sin x / x 夹在两个同极限对象之间。"
  bound_to: [limit-existence-criteria, limit-operation-and-substitution]
  tags: [squeeze, important-limit]

- id: c05
  title: 用单调有界准则引出 e
  type: case
  source_chapter: 第六节
  source_quote: "单调有界数列必有极限。"
  summary: "教材用单调有界数列说明 (1+1/n)^n 的极限存在，并定义常数 e。"
  bound_to: [limit-existence-criteria]
  tags: [monotone, e]

- id: c06
  title: tan(2x)/sin(5x) 的等价替换
  type: case
  source_chapter: 第七节
  source_quote: "tan 2x ~ 2x，sin 5x ~ 5x。"
  summary: "教材用等价无穷小把三角函数商化为线性函数商。"
  bound_to: [equivalent-infinitesimal-substitution]
  tags: [equivalent-infinitesimal]

- id: c07
  title: 可去间断点的补定义
  type: case
  source_chapter: 第八节
  source_quote: "如果改变函数在 x=1 处的定义，那么成为连续。"
  summary: "教材用极限存在但函数值不匹配的例子说明可去间断点。"
  bound_to: [continuity-discontinuity-diagnostics]
  tags: [removable-discontinuity]

- id: c08
  title: 零点定理证明方程有根
  type: case
  source_chapter: 第十节
  source_quote: "f(0)=1>0，f(1)=-2<0，根据零点定理..."
  summary: "教材用连续函数端点异号证明三次方程在 (0,1) 内至少有一个根。"
  bound_to: [closed-interval-continuity-toolkit]
  tags: [zero-theorem, root]
```

