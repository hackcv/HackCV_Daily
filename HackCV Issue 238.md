+++
author = "cvley"
categories = ["资讯日报"]
title = "第49期 HackCV 日报"
tags = ["机器学习","神经网络"]
date = "2017-11-20"
+++

- [人脸识别详解第二部分：基准](http://blcv.pl/static/2017/11/08/demystifying-face-recognition-ii-baseline/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 人脸识别详解系列的第二篇，主要是不同网络结构的测试结果，一共22个网络结构，这个测试结果的表格可以详细了解下。

- [缩减的MNIST：机器学习使用小数据的效果如何](http://cognitivemedium.com/rmnist?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 简单有趣的实践，MNIST都是作为基准数据集用于测试算法的效果，这篇文章的思路很奇特，使用缩减后的MNIST进行不同算法的测试，又可以得到什么结果呢？首先使用SVM、kNN、决策树、随机森林和神经网络构建基准，之后进行不同的测试，与基准结果对比。最终效果最好的是构建新的神经网络和数据扩展后的算法，这显然与我们的期望是一致的。

- [什么是迁移学习](https://medium.com/@pranoyradhakrishnan/what-is-transfer-learning-8b1a0fa42b4?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 非常简短的transfer_learning的总结，简单来说，就是使用一个现有的模型，在新的数据集上训练全部或者部分layer，可以让新得到的模型解决相似的问题。如果新数据集比较小，最好只修改并重新训练最后一层；如果数据集比较大，可以使用现有模型的参数作为初始参数，全部进行重新训练。

