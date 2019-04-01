# WGAN-for-stochastic-dynamic-response-
using WGAN-gp to generate time history of the dynamic response for nonliner structures

相关参数设置如下：
训练集大小：200；
minibatch：20；
训练次数：1000；
每训练一次生成器训练50次判别器；
算法：Adam优化算法（μ取为0.5；v=0.999；参数学习率为0.0001）
