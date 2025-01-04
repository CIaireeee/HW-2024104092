# HW-2024104092

# 项目简介：
本项目旨在通过机器学习算法对信用卡审批数据进行二分类预测。通过对申请人的个人背景信息及消费行为记录进行分析，预测其信用卡申请是否会被批准。项目使用了决策树、支持向量机（SVM）和随机森林三种算法，并对模型的性能进行了评估和比较，最终确定随机森林为最优模型。

# 运行环境：
操作系统: Windows/Linux/MacOS \
Python 版本: 3.8 或更高版本
# 依赖包:
pandas: 1.5.3\
numpy: 1.24.3\
scikit-learn: 0.23.2\
matplotlib: 3.3.2\
seaborn: 0.11.0\
scipy: 1.5.2\
plotnine: 0.8.0\
ucimlrepo: 0.0.7

# 复现步骤：
下载数据集: 使用 ucimlrepo 包从 UCI 机器学习数据库下载信用卡审批数据集。\
运行代码: 打开 Jupyter Notebook，运行项目中的 credit_card_approval.ipynb 文件。该文件包含了数据预处理、模型训练和评估的完整代码。\
查看结果: 运行完成后，可以在 Notebook 中查看模型的性能评估结果，包括准确率、正类精确率和 AUC 值。

# 使用的库和函数：
plotnine: 用于数据可视化，类似于 ggplot2。\
matplotlib: 用于绘制图形。\
seaborn: 基于 matplotlib 的高级绘图库。\
scipy.stats.boxcox: 用于数据的 BOX-COX 变换。\
sklearn.preprocessing: 用于数据预处理，包括标准化和编码。\
sklearn.metrics: 用于评估模型性能，包括准确率、精确率和 AUC 值。
