# house-price-prediction

本人ML及DL验证项目使用

---

使用两种建模方法处理房价预测问题

1. PyTorch MLP (Deep Learning)
2. XGBoost (Machine Learning)

## MLP

1. EDA

- 目标右偏，使用log1p变换保证比较相对误差

- 识别强相关特征

2. 预处理

- 数值标准化

- 类别 one-hot

3. 模型试验

- 线性 baseline

- 两层 MLP

- L2 正则

- Dropout 实验（验证其不适合）

- K-fold 验证

- 模型对比

在小数据回归的情况中，浅层MLP提供的线性回归收益有限。
