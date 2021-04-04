+++
author = "cvley"
categories = ["资讯日报"]
title = "第105期 HackCV 日报"
tags = ["机器学习","神经网络"]
date = "2018-01-15"
+++

- [一个模型解决所有问题](https://blog.acolyer.org/2018/01/12/one-model-to-learn-them-all/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 这篇博客是对论文“One_model_to_learn_them_all”的详细解读。现有模型一般都只能解决特定问题，虽然迁移学习可以让现有模型扩展，但还是无法跨领域使用，比如解决图像的模型如何用于解决音频和文本信息。这篇论文是对这个问题的一个尝试，提出了一个叫做MultiModel的架构，输入可以是多种样式，输出也可以是多种样式，模型可以从中提取通用的知识表示。

- [使用Yelp数据来预测餐馆的倒闭情况](https://towardsdatascience.com/using-yelp-data-to-predict-restaurant-closure-8aafa4f72ad6?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 这篇文章的思路值得参考，首先定义问题，这是个分类的问题；接着构建数据集，可以说作者使用了各种方法来构建一个可用的数据集；接着就是特征工程了，这里着重分析了哪些特征对餐馆比较有影响；下面就开始选择合适的模型进行学习优化了；有了模型的结果，可以通过特征重要性和模型可译性方面对问题有更深的理解；最后就是进一步优化的方法和思路了。

- [机器学习的下一代，脉冲神经网络](https://towardsdatascience.com/spiking-neural-networks-the-next-generation-of-machine-learning-84e167f4eb2b?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 当前流行的人工神经网络虽然已经在一些领域大放异彩，但它们并非真正模拟人脑。而机器学习的第三代，脉冲神经网络，所要解决的就是神经科学和机器学习之间的连接。顾名思义，脉冲神经网络的输入是脉冲，不再是连续的数值。当一个神经元接收了脉冲，其势能会增加，当势能达到一定程度后，就会发射脉冲，而神经元也会被重置。目前脉冲神经网络还在研究之中。

