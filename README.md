# chemistry-prediction
homework
目前更新任务：
从“预测效果”角度建议的下一步改进

做 5-fold 交叉验证并报告均值±标准差，减少单次划分偶然性。
损失函数试一下 HuberLoss（对少量异常点更稳），通常能进一步降RMSE。
MLP加轻量正则（weight decay）和学习率调度器，常见能提升泛化。
在不改任务定义前提下，做简单集成（3-5个不同seed模型取均值），往往能再提一点测试表现。
报告 MAE alongside RMSE，便于解释“平均误差大概多少logS单位”。
