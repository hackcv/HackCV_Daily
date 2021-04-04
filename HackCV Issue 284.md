+++
author = "cvley"
categories = ["资讯日报"]
title = "第90期 HackCV 日报"
tags = ["深度学习","AI","TensorFlow","git","AlphaGo"]
date = "2017-12-31"
+++

- [现在谷歌使用AI生成的语音已经和人没有区别](https://qz.com/1165775/googles-voice-generating-ai-is-now-indistinguishable-from-humans/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 谷歌新发表的文章描述了最新的文字转语音的系统，叫做Tacotron_2，从提供的两段音频，无法区分哪个是人说的，而且对于大写单词还会加强语气。这个系统使用了两个深度网络，一个把文字转换为声谱图，声谱图进入第二个网络，即WaveNet，进而得到语音。

- [通过深度学习和树搜索使用快慢思考的方法从零开始学习](https://davidbarber.github.io/blog/2017/11/07/Learning-From-Scratch-by-Thinking-Fast-and-Slow-with-Deep-Learning-and-Tree-Search/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 本文属于强化学习的范畴，所谓的快慢思考模拟的是人类的多进程原理，即处理问题时的两种形式，一种是快速响应的、无意识的自动模式，一种是缓慢的、清醒的、基于规则推理的模式。目前已有的强化学习并没有采用第二种模式，第一版的AlphaGo依旧是基于人类棋谱作为样本学习的。作者在发表的论文中提出了专家迭代这样一个通用的学习框架，可以看做是模仿学习方法的一种扩展，这倒是与AlphaGo_Zero相似，有兴趣的可以研究下这篇论文。

- [截肢的音乐家使用AI义肢再次弹奏钢琴](https://blogs.nvidia.com/blog/2017/12/28/ai-prosthesis-skywalker/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 看了视频非常震撼，通过超声波探针探测胳膊的运动信息，使用TensorFlow构建深度学习网络监测肌肉运动，从而预测要控制的是哪个手指。

