# L1  与 L2  的区别？

- 都是针对参数的正则化。（即针对权重W的正则化)
    - W 的权重，决定模型曲线的形状
    - B 不会改变模型曲线
- L1和L2范数
    - 范数: 把空间中两点的距离这个概念 进行了扩充
- 闵可夫斯基距离
    - l1 = 1维 （曼哈顿距离）
    - l2 = 2维 （欧式距离）
    - lp范数，但只有p >= 1 才是凸集函数
      - 凸优化问题？

> 下图 的方块为 L1 函数，右侧为 L2函数

![](https://pic3.zhimg.com/80/v2-2e038f7a54e885714a7bf5ab9c5dda56_1440w.jpg)

$$
l1: \left\| W \right\|_1 = |w_1| + |w_2|+...+|w_i| = \sum_i {|w_i|}  \\

l2: \left\| W \right\|_2 = \sqrt{w_1^2 + w_2^2 +...+w_i^2} =  \sqrt{\sum_i w_i^2}  \\
$$


### 什么是正则化 (Regularization)？

- 正则化用于减缓过拟合问题的手段。
- 与正则表达式(Regular Expression) 没有关系。
- 不只有 L1 和 L2


### 正则化的定义

- 凡是可以减少泛化误差, 而不是减少训练误差的方法，都可以叫做正则化。
- 减少过拟合的方法，称为正则化方法。