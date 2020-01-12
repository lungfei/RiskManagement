# 特征选择的目的
## 特征选择目标是寻找最优特征子集，剔除不相关(irrelevant)或冗余(redundant)的特征，提高模型精确度，减少运行时间。

# 特征选择的原因
## 过拟合
## 奥卡姆剃刀原理
## 无用输入和输出

# 特征选择的方法
## 过滤法(Filter) 列入一些筛选特征的标准，比如皮尔逊相关系数、卡方分布
### 信息增益
### 卡方验证(chi-square test)
### 互信息和最大信息系数 Mutual information and maximal information coefficient (MIC)
### fisher score
### 皮尔逊相关系数
### variance threshold

## 包装法(Wrapper) 包装法将特征选择看作是搜索问题，例如递归特征消除
### 递归特征消除

## 嵌入法(Embedded) 嵌入法使用内置了特征选择方法的算法。比如lasso和RF都有各自的特征选择方法
### L1(LASSO)正则
#### 逻辑回归
### 基于树模型
#### 随机森林
#### LightGBM
#### XGBoost


# 参考
## 源码
### https://www.kaggle.com/mlwhiz/feature-selection-using-football-data
## 文章
### https://juejin.im/post/5d7b12e26fb9a06b2650c49a
### https://www.kesci.com/home/project/5d26c5b4688d36002c58bf5f



