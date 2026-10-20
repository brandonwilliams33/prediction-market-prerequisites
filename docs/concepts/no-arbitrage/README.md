# 无套利定价

本分类整理有限结果预测市场中的价格一致性几何，以及如何理解理论套利机会。

- [凸包（Convex Hull）](convex-hull.md)：描述无摩擦条件下可由结果状态概率加权得到的价格向量集合。
- [套利空间（Arbitrage Region）](arbitrage-region.md)：描述无套利价格集合之外的报价，以及实际执行时需要检查的限制。

若要量化价格向量偏离无套利集合的程度，可参见数学前置中的[曼哈顿距离（L1 距离）](../../math-prerequisites/geometry-and-optimization/manhattan-distance.md)。几何距离用于衡量偏离，不直接等同于套利利润。

这类结论依赖支付向量、可交易组合、现金/抵押品约定和交易约束。现实市场需将理论边界与 Bid/Ask、深度、手续费、卖空/头寸限制及结算风险区分开来。
