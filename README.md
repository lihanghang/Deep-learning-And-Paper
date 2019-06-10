# 机器智能--相关书目及经典论文

---
## 探索自动机器学习
### 论文资料
- [AutoML-papers](./AutoML资料汇总)  
### 主要分类
| 序号     | 中文名称          |  英文名称  |
| -------- | -----:           | :----: |
| 1        | 自动数据清洗      |Automated Data Clean, Auto Clean    |
| 2        | 自动特征工程      |Automated Feature Enginnering,  Auto FE    |
| 3        | 神经网络架构搜索  |Neural Architecture Search, NAS|
| 4        | 超参数优化        |Hyperparameter Optimization, HPO|
| 5        | 元学习            |Meta-Learning|

### 主要开源工具
|序号|	名称	|简介	|链接|	主要特点|	主要技术|	备注|
| -------- | :----- | :----: |    :------ |:----------- |:------ |:------ |
|1|	Auto-Keras|	Auto-Keras是一个用于自动机器学习（AutoML）的开源软件库。它由Texas A＆M大学的DATA实验室和社区贡献者开发。|	https://autokeras.com/	Auto-Keras提供自动搜索深度学习模型的架构和超参数的功能。	|用神经架构搜索，但应用“网络态射”（在更改架构时保持网络功能）以及贝叶斯优化，以指导网络态射以实现更高效的神经网络搜索。|	德克萨斯州A&M大学数据实验室团队|
|2|	Auto-sklearn|	是一个自动化机器学习的工具包,其基于sklearn编写。|	https://automl.github.io/auto-sklearn/master/#|	仅支持监督学习的分类和回归。框架可以自动进行数据预处理，特征预处理，（分类/回归）算法选择，最终可导出模型，存储并使用。 |	Bayesian Optimization/SMAC (sequential model-based algorithm configuration)等|	Frank Hutter 等|
|3|	NNI-v0.8|	NNI（神经网络智能）是一个帮助用户运行自动机器学习（AutoML）实验的工具包。该工具调度并运行由优化算法生成的试验作业，以在不同的环境(如本地机器、远程服务器和云)中搜索最佳的神经体系结构和/或超参数。|	https://github.com/Microsoft/nni	|支持私有部署/支持分布式调度/对超参搜索的底层支持|	Random Search/ Tree-structured Parzen Estimator (TPE) /Grid Search等|	微软发布|
|4|	TransmogrifAI |	是一个基于Scala和SparkML构建的Java开源库，用于处理结构化数据的端到端自动化机器学习库。|	https://transmogrif.ai/	|可以自动完成数据清理、特征工程和模型选择，然后训练出一个高性能模型，进行进一步探索和迭代。|	基于自动类型的特征工程/特征验证等|	Salesforce发布|

### 商业化平台
|序号|	系统名称	|类型|	链接	|主要功能|	备注|
| -------- | -----:           | :----: |    :------ | :------ | :------ |
|1|	Cloud AutoML	|商业	|https://cloud.google.com/automl/|	NLP/翻译/视觉/视频等。|	 Google 发布|
|2|	PAI Studio|	商业	|https://help.aliyun.com/document_detail/114522.html?spm=a2c4g.11186623.6.565.29d819ceRPvkKG	|提供了从数据处理、模型训练、服务部署到预测的一站式服务，PAI Studio可视化建模作为其子产品。自动调参等。	|阿里云发布|
|3|	EasyDL|	商业	|http://ai.baidu.com/easydl/	|图像分类/物体检测/文本分类/声音分类/视频分类/商品检测专业版	| Baidu 发布|
|4|	 DarwinML|	商业|	http://iqubic.net/sy	|计算机视觉，自然语言处理，对话流程和机器学习等。|	探智立方发布|
|5|	小智|	商业	|https://www.wisutech.com/#/product	|自动构建高精度模型/简单易用、全程可视化/模型快速部署/支持海量数据建模等。|	智铀科技发布|
|6|	第四范式先知AutoML	|商业	|http://www.4paradigm.com/product/automl	|数据管理/自动模型工程，模型自我迭代，抗衰减/自动上线模型并运维监控等。|	第四范式发布|
|7	|深思平台|	商业	|https://www.zhiyi.cn/|	数据导入/特征工程/模型训练/模型托管等。|	智易科技发布|

--------------------- 

#### 研究体悟
1. 算法是死的，思想是活的。经典反复多次，悟其背后之道，才可唯我所用。  
2. 理论实践相结合。
#### 论文资料
- activation.激活函数
- Attention. 注意力机制
- GANs
- 深度森林
- 声学模型
- 声纹识别
- 语音合成
#### 实验代码  
- 情感分析  
对中文电影评论进行情感分析  
- 语音识别  
对英文数字语音进行别  
- 声纹识别  
#### 幻灯(论文资料中)
- GAN
- Deep Forest
#### 书目
- 动手学深度学习  
- 神经网络与深度学习  
- 语音与语言处理（第3版）
- 一份不太简短的LATEX介绍
- Hands-On+Machine+Learning+with+Scikit-Learn+and+TensorFlow
---  
Update:20190610

