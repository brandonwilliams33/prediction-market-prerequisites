# 几何与优化

本分类收录预测市场分析中用到的向量几何、凸集和优化工具。

- [曼哈顿距离（Manhattan Distance / L1 Distance）](manhattan-distance.md)：计算市场价格向量到无套利凸集的最小 L1 距离。

## 相关概念

- [无套利定价](../../concepts/no-arbitrage/README.md)：凸包与套利空间的定义及假设。
- [凸包](../../concepts/no-arbitrage/convex-hull.md)：在简化的无摩擦模型中描述一致价格集合。

价格到集合的距离是几何偏离度量，不应直接视为可实现利润。使用时需保持价格单位、状态支付和交易约束的约定一致。
