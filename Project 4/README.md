# 受限玻尔兹曼机

## 问题描述：

​	使用受限玻尔兹曼机（Restricted Boltzmann Machine, RBM），对MNIST 数据集建模。其中，每个
像素点（值为0 或1）作为可观测变量，同时自定义一组隐变量（隐变量的个数为超参），完成以下任务：

1. 使用不带标签的MNIST 样本数据，训练RBM 参数。
2. 根据第1 步训练出的RBM，使用Gibbs 采样的方法，生成一组服从分布的样本。

## 数据集: 
 	MNIST数据集包括60000张训练图片和10000张测试图片。图片样本的数量已经足够训练一个很复杂的模型（例如 CNN的深层神经网络）。
 	它经常被用来作为一个新 的模式识别模型的测试用例。而且它也是一个方便学生和研究者们执行用例的数据集。除此之外，MNIST数据集
 	是一个相对较小的数据集，可以在你的笔记本CPUs上面直接执行

## 题目要求： 
- [ ] 请使用代码模板rbm.py，补全缺失部分，尽量不改动主体部分。
- [ ] 请使用对比散度方法训练
- [ ] 推荐使用python 及numpy 编写主要逻辑代码，适度使用框架。