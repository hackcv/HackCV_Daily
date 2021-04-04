+++
author = "cvley"
categories = ["资讯日报"]
title = "第99期 HackCV 日报"
tags = ["机器学习","RNN","词袋模型","神经网络"]
date = "2018-01-09"
+++

- [算法效率来自于问题的信息](http://www.stochasticlifestyle.com/algorithm-efficiency-comes-problem-information/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 非常赞同文中的观点，对问题的信息了解的越多，解决的方法就越高效，这也是为什么定制化的算法更快的原因。文中举了几个数学的例子来证明，事实上，这就是“知己知彼，百战不殆”。

- [自动Bug处理](http://bugtriage.mybluemix.net/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 无论什么东西，数量上去了，就会考虑自动化处理。本文是对提交的BUG进行自动处理的尝试，对于比较大的系统，人工处理几十上百万条BUG确实不易，而这对于机器学习则是一个简单的分类问题：输入是BUG的标题和内容，输出是对应的类别或者开发者。本文使用基于深度双向循环神经网络（DBRNN-A）这个模型来处理这个问题。通过与词袋模型、softmax分类器、支持向量机、朴素贝叶斯和余弦距离相比，该方法的效果最好。

- [Meltdown缺陷和KPTI补丁：对ML的性能有什么影响](https://medium.com/implodinggradients/meltdown-c24a9d5e254e?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 新年伊始，就出现了两个大的问题，Meltdown和Spectre。它们是处理器的bug，可以让攻击者读取不属于自己进程的内存信息。最新的Linux内核已经合并了一个补丁修复这些问题，但带来的副作用是CPU的性能会降低5%到35%左右。本文作者探索了这个补丁对ML的性能的影响，发现基本没什么影响，只是会对特定的算法有较大影响，比如QR分解，比如使用过多线程。

