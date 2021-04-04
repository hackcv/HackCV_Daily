+++
author = "cvley"
categories = ["资讯日报"]
title = "第68期 HackCV 日报"
tags = ["目标检测","YOLO","机器学习","Jupyter","数据科学"]
date = "2017-12-09"
+++

- [IBM科学家证明使用GPU可以在大规模数据集上得到10倍加速](https://www.ibm.com/blogs/research/2017/12/10x-faster-using-gpu/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 因为GPU的显存有限，所以训练时都会采用batch批量处理，大量的时间花费在了数据吞吐上。IBM的这篇文章阐述了一个全新的角度来加速这个训练过程，虽然显存容量和数据吞吐能力有限且无法修改，但数据是可以优化的，因而提出了一个基于Duality-gap的多样学习架构，其创新点在于可以获取单个样本在训练过程中可以贡献的信息数量，这样就可以在训练过程中跳过那些已经学习到特征的样本，从而加速整个训练过程。论文地址https://arxiv.org/pdf/1708.05357.pdf，可以研究一下。

- [使用数据科学如何写一首圣诞歌](https://www.lynchpin.com/blog/how-to-write-a-christmas-song-using-data-science/?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 数据科学，更多是在数据分析，本文使用的是哥伦比亚大学提供的“百万歌曲数据集”，通过一些圣诞关键字提取了3136首圣诞相关的歌曲信息，进而从数据分析角度提供了这些歌曲的一些信息和规律。然后使用Python的NLTK自然语言工具集对歌词进行处理聚类，找出得到的三类中使用频率较高的词汇集合，从这个集合中随机生成歌词，再人工加工。从最后的歌词来看，效果确实挺不错。

- [使用机器学习计算人数](https://www.byu.io/2017/12/07/counting-people-with-ml?from=hackcv&hmsr=hackcv.com&utm_medium=hackcv.com&utm_source=hackcv.com)

> 从Insecam抓取摄像头拍摄的视频，使用Python+YOLO进行目标检测，最后使用Jupyter、Pandas和Matplotlib绘制结果进行分析。结论是实验效果出奇的好，YOLO很强大。

