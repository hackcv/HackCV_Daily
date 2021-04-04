+++
author = "cvley"
categories = ["资讯日报"]
title = "第67期 HackCV 日报"
tags = ["RNN","卷积","TensorFlow","神经网络","卷积神经网络","入门"]
date = "2017-12-08"
+++

- [可视化卷积神经网络](https://www.oreilly.com/ideas/visualizing-convolutional-neural-networks?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 这篇文章很值得一看，不同于使用现有模型，文中构建了一个简单的四层网络，显然最后得到的模型精度一般，但却可以完全对卷积操作进行非常全面的操作，进而可以更深入的理解卷积。文中有代码和解释，使用的是TensorFlow，但选择自己构建卷积，而不是使用已有的高级接口。

- [不是另一个使用TensorFlow进行的MNIST教程](https://www.oreilly.com/learning/not-another-mnist-tutorial-with-tensorflow?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> end-to-end的入门级TensorFlow教程，提供了Ubuntu环境下使用Python3和TensorFlow进行MNIST实验的全过程，推荐初学者看看。

- [基准测试：英伟达P100与V100这两款GPU的PK](https://www.xcelerit.com/computing-benchmarks/insights/benchmarks-deep-learning-nvidia-p100-vs-v100-gpu/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 测试使用的是TensorFlow，使用RNN和LSTM的训练和推断进行测试对比，发现V100的性能仅仅比P100提供了一点点，差不多1.7x的样子。V100内置单精度4x4矩阵相乘优化，但这两个模型并没能很好的利用这个性能，大概TensorFlow还没针对此特性进行优化。文中没有提供测试代码，看看就好。

