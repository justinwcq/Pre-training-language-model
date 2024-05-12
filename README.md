# Pre-training-language-model

配套视频链接：https://www.bilibili.com/video/BV1At4y1W75x?spm_id_from=333.999.0.0；

配套博客链接：https://www.cnblogs.com/nickchen121/p/15105048.html

第一篇 Transformer、GPT、BERT，预训练语言模型的前世今生（理论）
00 预训练语言模型的前世今生（全文 24854 个词）
03 什么是预训练（Transformer 前奏）
04 统计语言模型（n元语言模型）
05 神经网络语言模型（独热编码+词向量的起源）
06 Word2Vec模型（第一个专门做词向量的模型，CBOW和Skip-gram）
07 预训练语言模型的下游任务改造简介（如何使用词向量）
08 ELMo模型（双向LSTM模型解决词向量多义问题）
09 什么是注意力机制（Attention ）
10 Self-Attention（自注意力机制）
1001 Attention 和 Self-Attention 的区别（还不能区分我就真的无能为力了）
11 Self-Attention相比较 RNN和LSTM的优缺点
12 Masked Self-Attention（掩码自注意力机制）
13 Multi-Head Self-Attention（从空间角度解释为什么做多头）
14 Positional Encoding （为什么 Self-Attention 需要位置编码）
1401 位置编码公式详细理解补充
15 Transformer 框架概述
16 Transformer 的编码器（Encodes）——我在做更优秀的词向量
17 Transformer 的解码器（Decoders）——我要生成一个又一个单词
18 Transformer 的动态流程
19 Transformer 解码器的两个为什么（为什么做掩码、为什么用编码器-解码器注意力）
第二篇 第二篇 通过 Pytorch 构建 Transformer 框架（真实战，不做调包侠）
00 通过 Pytorch 实现 Transformer 框架完整代码
000 通过 Pytorch 实现 Transformer 框架完整代码（带注释）
02 Transformer 中 Add&Norm （残差和标准化）代码实现
0201 为什么 Pytorch 定义模型要有一个 init 和一个 forward，两者怎么区分
03 Transformer 中的多头注意力（Multi-Head Attention）Pytorch代码实现
04 Transformer 中的位置编码的 Pytorch 实现
05 Transformer 中的前馈神经网络（FFN）的实现
第三篇 Huggingface 实战（待续）
推荐阅读
pytorch从入门到放弃（目录）
Python从入门到放弃（目录）
人工智能从入门到放弃（目录）
数据结构与算法-江西师范大学865（针对考研or面试）（目录）
十天快速入门Python（目录）
数据结构与算法-Python/C（目录）
Go从入门到放弃（目录）
TensorFlow2教程-旧（目录）
机器学习-项目杂记（目录）
Python能干啥-项目杂记（目录）
大数据分析和人工智能科普
人工智能（机器学习）学习之路推荐
推荐书单（网课）-人生/编程/Python/机器学习
曾Python培训讲师-Python开发无包装简历
