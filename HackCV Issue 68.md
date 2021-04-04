+++
author = "cvley"
categories = ["资讯日报"]
title = "第161期 HackCV 日报"
tags = []
date = "2018-03-12"
+++

- [0.05的显著性是什么](http://www.p-value.info/2013/01/whats-significance-of-005-significance_6.html?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 本文回顾了使用0.05作为统计显著性的历史，0.1表示统计发生的概率很低，而0.01表示基本不会发生，而取0.05是比较合适的做法。

- [构建基于内容的搜索引擎第二部分：提取特征向量](http://www.deepideas.net/building-content-based-search-engine-feature-extraction/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 使用的特征向量非常简单，坐标位置+Lab色彩空间+对比度+稀疏度+时间信息，用于表示视频的视觉信息和上下文信息。

- [HALP：高准确率低精度训练算法](http://dawn.cs.stanford.edu/2018/03/09/low-precision/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 低精度表示使用更少的位bit来表示权重，在inference时影响并不大，但在训练时会显著的降低准确率，主要因为权重参数会在低精度下取整，导致误差变大。本文是斯坦福大学最新的研究，设计了一套新的随机梯度下降的变种算法，可以在使用低精度时，保持高准确性。

