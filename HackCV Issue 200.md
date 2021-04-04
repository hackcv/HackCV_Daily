+++
author = "cvley"
categories = ["资讯日报"]
title = "第280期 HackCV 日报"
tags = ["卷积","TensorFlow"]
date = "2018-07-09"
+++

- [使用TensorRT加速GPU上的TensorFlow推断](https://medium.com/tensorflow/speed-up-tensorflow-inference-on-gpus-with-tensorrt-13b49f3db3fa?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> TensorRT可以加速推断，主要在于可以自动去除不适用的网络节点，从而减少计算量；而对于卷积、bias和ReLU层则会合并为一个层；此外，还有层聚合，将那些有相同源tensor和相似参数的相同operation进行合并。TensorRT不会修改图计算的过程，而是优化图的结构，

- [结构化TensorFlow模型](https://danijar.com/structuring-your-tensorflow-models/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 本文一步一步介绍了如何使用Python的装饰器，让TensorFlow的模型定义更加可读、更加易用。

- [XGBoostGPU算法的更新](https://xgboost.ai/2018/07/04/gpu-xgboost-update.html?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> XGBoost是非常流行的梯度提升算法工具，而现在更新了更多新的特性，加入了更快的算法，主要包括：基于梯度的树构建算法，速度提升了差不都4倍；使用AllReduce算法对多GPU进行支持，让算法可以随着GPU的数量增加获得线性加速的能力；此外，使用CSR格式对稀疏矩阵进行压缩，使得内存占用也减少了约三分之一。

