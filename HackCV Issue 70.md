+++
author = "cvley"
categories = ["资讯日报"]
title = "第163期 HackCV 日报"
tags = ["深度学习","机器学习","卷积","TensorFlow","git","神经网络","卷积神经网络","Keras","人工智能"]
date = "2018-03-14"
+++

- [使用Python和深度学习如何实现iPhone_X的FaceID](https://towardsdatascience.com/how-i-implemented-iphone-xs-faceid-using-deep-learning-in-python-d5dbaa128e1d?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 本文是对苹果手机的FaceID的逆向推理以及实现，结论是由类siamese的卷积神经网络实现这个功能，并使用Keras进行了实现，从结果看效果不错，代码开源在github上。

- [使用GAN变换字体风格](http://bair.berkeley.edu/blog/2018/03/13/mcgan/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 伯克利人工智能实验室对字体风格转换的研究，设计了一套GlyphNet，可以从少量的字体中学习到字体风格，进而完成风格转换。GAN确实很好很强大。

- [RiseML使用Horovod和TensorFlow支持分布式机器学习](https://blog.riseml.com/riseml-supports-distributed-deep-learning-with-horovod-and-tensorflow-40ac770d0009?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> Horovod是Uber开源的简化TensorFlow分布式训练的库，少量的修改就可以显著减少训练时间。它背后的原理是采用ring-allreduce算法进行权重通信，相对于使用参数服务器而言，可以做到线性扩展训练节点，而权重参数通信不会成为瓶颈。RiseML已经加入了Horovod的支持。

