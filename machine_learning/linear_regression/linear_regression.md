# linear regression

与分类一样，回归也是预测目标值的过程。回归于分类的不同在于，前者预测连续型变量，而后者预测离散型变量。在回归方程里，求得特征对应的最佳回归系数的方法是最小化误差的平方和。  

当数据的样本数目比特征数还少时，矩阵xTx 的逆不可计算。即便当样本数比特征数多时，xTx 的逆仍有可能无法计算，这是因为特征有可能高度相关。这时候可以考虑使用岭回归。  

为了使用岭回归和缩减技术，首先需要对特征做标准化处理，具体的做法是所有的特征都减去各自的均值并除以方差  

领回归是缩减法的一种，相当于对回归系数的大小做限制，防止过拟合现象的出现。 缩减法还可以看做是对一个模型增加偏差的同时减少方差。偏差方差折中是一个重要概念，可以帮助我们理解现有模型做出改进，从而得到更好的模型。

