# Test Summary

本轮未接入 darwin-skill 自动跑分器，但已按仓颉阶段 4 为每个 skill 写入 `test-prompts.json`。

## 覆盖要求

每个 skill 至少包含：

- `should_trigger`: 3 条
- `should_not_trigger`: 1 条
- `edge_case`: 1 条

## 人工压力测试关注点

- `function-mapping-diagnostics`: 不应抢普通极限题。
- `limit-definition-proof`: 只在定义证明场景触发，不应抢普通计算题。
- `equivalent-infinitesimal-substitution`: 对加减主项抵消题必须克制。
- `closed-interval-continuity-toolkit`: 不得在开区间连续题中误套最值定理。

## 下一步

若后续接入 darwin-skill，可直接读取各目录下的 `test-prompts.json` 做触发精度测试。

