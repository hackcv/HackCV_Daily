+++
author = "cvley"
categories = ["资讯日报"]
title = "第122期 HackCV 日报"
tags = ["神经网络"]
date = "2018-02-01"
+++

- [让xgboost和LightGBM速度最快：编译器和CPU绑定技术](https://medium.com/@Laurae2/getting-the-most-of-xgboost-and-lightgbm-speed-compiler-cpu-pinning-374c38d82b86?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 本文尝试使用编译器和CPU绑定技术来加速XGBoost和LightGBM，最终的结论是尽可能使用Visual_Studio的编译器，训练模型时不使用CPU绑定，尽量使用更高的CPU频率。事后诸葛亮一把：这些模型都是非常消耗计算力的，显然更高的CPU频率会有更好的加速效果，而CPU绑定可以提供缓存的命中率，降低调度开销，但在大规模的计算面前，这两种情况几乎没什么影响。这么看来，微软的编译器确实给力。

- [Twitter使用快速神经网络进行智能缩略图生成](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2018/Smart-Auto-Cropping-of-Images.html?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 现有的图片缩略图一般都是居中裁切，Twitter对此进行了优化，基于显著性进行裁切，优化用户体验。他们对现有用于显著性检测的深度网络进行了知识蒸馏和裁枝，可以实时处理图片，对应的剪枝算法论文https://arxiv.org/abs/1801.05787。

- [理解AttnGAN：文本图像转换器](https://codeburst.io/understanding-attngan-text-to-image-convertor-a79f415a4e89?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 本文是对AttnGAN论文的原理解读，包含了GAN的基本知识，AttnGAN这篇论文的两个创新点：多级图像修复和多情态动词结构损失。

