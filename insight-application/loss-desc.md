## 相关功能介绍    
 ![](/assets/liushifengxi/1.png)
  ![](/assets/liushifengxi/2.png)
  ![](/assets/liushifengxi/3.png)
 
### 模型结果（模型效果）
模型效果是展示模型对该训练集的效果平台，评估指标有两个，精确率和召回率，如下：
*	精确率:指的是后台算法对该模型预测流失数据的精确度的评估。
*	召回率:指的是后台算法对该模型预测流失数据的召回度的评估。
在训练过程中会把训练数据随机分成五份，其中四份用于训练，一份用于模型验证，比如本训练的模型的精确率：48.08%，召回率：12.69%，代表该训练模型精确度和召回度的情况。
### 模型结果（规则集）
规则集是描述该模型的规则集合，按照规则条件展示该条规则下用户是否流失、用户总记录数、流失用户数、不流失用户数、流失率等相应参数。
### 模型结果（模型输出）
以二叉树的方式来展示规则集之间联系。
### 使用模型预测和历史预测记录
*	使用模型预测：使用该模型进行数据预测。
*	历史预测记录：指的是该模型对应历史预测记录。