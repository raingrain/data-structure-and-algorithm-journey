# 四边形不等式的使用要求

> - 二维dp。
> - 填一个普遍位置时有枚举行为。
> - 当两个参数固定一个，另外一个参数与答案之间有单调性，并且两个参数与答案的单调性相反。
> - 不等式的优化来源与左 + 下或者上 + 右，其位置在求解时对应的最好选择点作为当前枚举时的下限和上限。
> - 能把时间复杂度降低一阶。
> - 等于时要不要优化直接用对数器验证。
> - 四边形不等式不一定是最优解。
