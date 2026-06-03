# Rejected Candidates

## r01 基本初等函数背诵表

- rejected_by: V2 预测力不足
- reason: 它是知识清单，不是可执行方法。agent 本身可以查表或引用，没必要独立触发。
- downgraded_to: glossary

## r02 双曲函数公式推导

- rejected_by: V1 跨域不足
- reason: 第一章只在第一节补充双曲函数及反双曲函数，后续章节没有足够独立语境支撑。
- downgraded_to: example/reference

## r03 函数奇偶性独立 skill

- rejected_by: V3 独特性不足
- reason: 奇偶性判断很重要，但单独做 skill 容易变成基础规则。已并入 `function-mapping-diagnostics` 的函数性质诊断。
- downgraded_to: subroutine

## r04 机械刷题答案生成

- rejected_by: 目标不符
- reason: 仓颉产物应是可迁移程序，不是逐题答案库。
- downgraded_to: test prompts

