+++
author = "cvley"
categories = ["资讯日报"]
title = "第136期 HackCV 日报"
tags = ["深度学习","深度学习引擎"]
date = "2018-02-15"
+++

- [使用kd-tree高效计算3D矢量空间的最近邻](http://blog.krum.io/k-d-trees/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 基于CSS色彩构建的kd-tree，用于搜索最近邻色彩，最后的图片测试结果挺有意思。

- [真正有效的自动学习率调度](http://blog.dlib.net/2018/02/automatic-learning-rate-scheduling-that.html?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 现有学习率的调整都是预先设定规则，在达到固定次数的迭代或者误差不再减小后就进行降低。本文是Dlib团队提供地自动调整学习率的方法，对学习率的趋势进行估计，进而让计算机可以自动控制学习率，同时也可以提前发现学习率的上升情况。如果使用dlib库的话，可以直接使用count_steps_without_decrease()和count_steps_without_decrease_robust()的C++和Python接口。

- [并行计算的量化模型及其在深度学习引擎里的应用](https://mp.weixin.qq.com/s/g4u8Azc7Ca1kcfNj8oLWBQ?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 一流公司对怎么更快的训练深度学习模型的分享，里面提到了Roofline模型，就是一种根据访存带宽，计算单元峰值吞吐率，任务的运算强度三者关系来推断实际计算性能的数学模型，并讨论了最大化系统的计算性能的几种方法。

