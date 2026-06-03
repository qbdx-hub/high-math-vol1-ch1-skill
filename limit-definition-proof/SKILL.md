---
name: limit-definition-proof
description: |
  用于用户要求“按定义证明极限”“用 epsilon-N 证明数列极限”“用 epsilon-delta 证明函数极限”“证明连续的定义”。不用于只想快速计算极限值的题，除非用户明确要求定义证明。
source_book: 《高等数学》上册 第七版 同济大学数学系
source_chapter: 第一章 第二节、第三节、第八节
tags: [limit, proof, epsilon, delta]
related_skills: [infinitesimal-limit-conversion, limit-operation-and-substitution]
---

# Limit Definition Proof

## R - 原文

> 对于任意给定的正数 epsilon，总存在正整数 N。
>
> - 同济大学数学系，第一章第二节

## I - 方法论骨架

极限定义证明的核心是量词顺序。
先把目标写成“要让某个差值小于 epsilon”。
然后对差值做代数估计，找出让它小于 epsilon 的充分条件。
数列极限要把条件转成 `n>N`；函数极限要把条件转成 `0<|x-x0|<delta`。
正式书写时要反过来：任取 epsilon，取合适的 N 或 delta，于是目标不等式成立。

## A1 - 书中的应用

### 案例 1: 数列极限定义

- 问题: 证明数列收敛到某常数。
- 方法论的使用: 教材反复展示“找出一个符合定义要求的正整数 N”的方法。
- 结论: 证明不是观察趋势，而是给出对任意 epsilon 都有效的尾部控制。
- 结果: 收敛性被转化为可验证的不等式。

### 案例 2: 函数极限定义

- 问题: 证明 `x->x0` 时函数极限为 A。
- 方法论的使用: 教材把 `|f(x)-A|<epsilon` 与 `0<|x-x0|<delta` 联系起来。
- 结论: delta 通常从目标误差反推得到。
- 结果: 极限证明有固定模板。

## A2 - 触发场景

### 用户会在什么情境下需要这个 skill?

1. 明确要求“用定义证明”某个极限。
2. 要证明某数列收敛，而不是只求极限值。
3. 要说明函数在某点连续，并要求用定义表达。
4. 对 epsilon、delta、N 的取法困惑。

### 语言信号

- “按定义证明”
- “epsilon-delta 怎么写”
- “epsilon-N 证明”
- “怎么取 delta”
- “这个极限的严格证明”

### 与相邻 skill 的区分

- 与 `limit-operation-and-substitution` 的区别: 本 skill 强调严格定义证明；后者用于计算。
- 与 `infinitesimal-limit-conversion` 的区别: 本 skill 写量词证明；后者把极限转成无穷小代数。

## E - 可执行步骤

1. **写出目标不等式**
   - 完成标准: 数列写 `|x_n-a|<epsilon`；函数写 `|f(x)-A|<epsilon`。

2. **反推控制条件**
   - 完成标准: 通过代数变形找出 `n>N` 或 `|x-x0|<delta` 的充分条件。

3. **选择 N 或 delta**
   - 完成标准: 给出显式选择，如 `N > 1/epsilon` 或 `delta=min(1, epsilon/C)`。

4. **正向回写证明**
   - 完成标准: 从“任取 epsilon”开始，按定义完整推出目标不等式。

## B - 边界

### 不要在以下情况使用

- 用户只要求快速算极限，且没有要求严格证明。
- 题目需要洛必达、泰勒或导数工具，而当前试点只覆盖第一章。

### 失败模式

- 先假设极限成立再证明极限成立。
- delta 依赖于 x，而不是只依赖 epsilon 和固定参数。
- 忘记函数极限定义中的去心条件。

