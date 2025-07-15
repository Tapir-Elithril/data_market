# A Marketplace for Data An Algorithmic Solution
## Introduction
### data feature
### market model
## Model
### sellers
### buyers
#### prediction task
#### prediction gain function
#### accuracy value（估值）
#### public bid（出价）
### marketplace
#### price
#### prediction algorithm(ml,M)
#### allocation function(AF)
#### (seller)revenue function(buyer pay)(RF)
#### payment division function(PD)
#### price update function(PF)
### marketplace dynamics
## marketplace properties
### truthfulness
### revenue maximization
### fair revenue division
#### Shapley fairness:O(2^M)
#### Robustness to replication:无限复制对收益增长有限
### computational efficiency:O(M)
## Marketplace Construction
### AF:
#### 简化X_M
#### compare b_n & p_n
#### 保留价不适用
### RF:Myerson's payment function
### PF:MWU:利用收益g更新权重w
### PD:
#### Shapley值的计算：k采样
#### 近似数据惩罚：Shapley值削减（根据复制数量e指数降低）
## Main Results
### Assumptions
#### AF单调递增
#### 复制数据不增加模型准确度
#### RF是L连续
#### 投标范围有限
### Truthfulness
### Revenue Maximization
### Fairness in revenue division

## 定理证明
