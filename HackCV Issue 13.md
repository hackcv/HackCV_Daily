+++
author = "cvley"
categories = ["资讯日报"]
title = "第111期 HackCV 日报"
tags = ["自然语言处理","RNN","TensorFlow","神经网络","word2vec"]
date = "2018-01-21"
+++

- [使用TensorFlow进行LSTM的介绍](https://www.oreilly.com/ideas/introduction-to-lstms-with-tensorflow?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 长短期记忆神经网络竟然已经存在了20年了！LSTM是RNN的一种特例，主要对连续数据进行建模，常用于自然语言处理任务。这篇文件对LSTM的结构进行了介绍，并使用TensorFlow进行了股票信息模型的训练。

- [通过OpenFace理解人脸识别](https://blog.algorithmia.com/understanding-facial-recognition-openface/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> OpenFace的一个特色是关注于在手机设备上的实时人脸识别，但从使用语言看，应该还有一段路要走。具体来说是使用Torch训练人脸特征表示的神经网络，然后使用dlib中的人脸检测器检测人脸，并对每个人脸进行预处理，之后使用前面训练的神经网络提取人脸特征，最后使用svm分类即识别是谁。

- [亚马逊BlazingText：在多CPU或GPU中并行的Word2Vec版本](https://amazonaws-china.com/cn/blogs/machine-learning/amazon-sagemaker-blazingtext-parallelizing-word2vec-on-multiple-cpus-or-gpus/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 主要是对BlazingText的评测，从结果看，对比fastText，数据吞吐提升明显，准确率变化非常小，但采用batch_skipgram这种训练方式，显然数据吞吐会有提升。从成本的角度看，确实降了不少，而且使用多实例进行并行训练时，也有sub-linear的吞吐提升。

