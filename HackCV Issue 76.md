+++
author = "cvley"
categories = ["资讯日报"]
title = "第169期 HackCV 日报"
tags = ["RNN","TensorFlow","入门","Keras"]
date = "2018-03-20"
+++

- [理解LSTM并使用Keras快速构建用于情感分析](https://towardsdatascience.com/understanding-lstm-and-its-quick-implementation-in-keras-for-sentiment-analysis-af410fd85b47?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 本文是一篇入门教程，先介绍了RNN和LSTM的概念和结构组成，以及一些激活函数的使用原因，然后是使用Keras实现LSTM，对文本情感进行分析。

- [TensorFlow的tf.image.resize是如何偷走了我人生中的60天](https://hackernoon.com/how-tensorflows-tf-image-resize-stole-60-days-of-my-life-aba5eb093f35?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 从标题中就可以看出，本文不建议使用tf.image.resize。作者的经历总结下来就是：一个像素导致的惨案！作者的应用是对图像超分辨，本来使用OpenCV和PIL效果非常好，但完全移植到TensorFlow后，从PSNR等量化角度，发现效果变差了，经过60天的辛苦排查，发现是tf.image.resize_bicubic有个校准参数，导致得到图像有像素级别的平移，PSNR计算的是图像同位置像素值的关系，果断变差了。

- [NeuroNuggets：年龄和性别预测](https://medium.com/neuromation-io-blog/neuronuggets-age-and-gender-estimation-2807b1307a13?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> NeuroNuggets的宣传文章，介绍了年龄和性别预测的基础知识，以及如何在他们的平台上使用这个模型。里面涉及到的一些信息，包括使用HOG和SIFT作为特征，使用SVM进行人脸检测，年龄估计使用WRN网络。

