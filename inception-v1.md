## 1. 1*1 卷积核的作用
1. 降低维度，减少计算瓶颈的发生
2. 增加网络的深度和宽度
3. 更加容易整合到CNN的pipeline上

## 2. 增加网络深度来增加性能缺点
1. 网络越深，参数就越多。容易导致过拟合。尤其是在样本量少的情况下，而且高质量的样本创建是棘手且昂贵的
2. 成倍的增加计算量的

## 3. inception模块
1. module
![inception模块](https://github.com/lmm915815/DeepLearningPaperSummary/blob/master/picture/inception%E6%A8%A1%E5%9D%97.png)

2. 为什么需要 1 * 1、3 * 3、5 * 5的内核

`1. 基于方便考虑而不是必须这个大小`
`2. `

3. 为什么需要加上1*1过滤器