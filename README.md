# Machine-Learning-based-on-courses
Records about Machine Learning courses

## 介绍
基于机器学习与模式识别课程的知识点总结和梳理

### python机器学习软件包
参考课件> http://justinruan.gitee.io/learning-ml/%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0%E4%B8%8E%E6%A8%A1%E5%BC%8F%E8%AF%86%E5%88%AB00.2.%20Python%20Tools%202020.05.13.pdf
主要介绍了简单算法、案例、数据集等。

### 机器学习基础知识
- 机器学习.是一个计算机程序，针对某个特定的任务，从经验中学习，并且越做越好。可以应用于语音识别、搜索引擎、自动驾驶等。
- 机器学习的分类：有监督学习（回归学习、分类学习），无监督学习（聚类），半监督学习，强化学习

- 有监督学习：通过大量已知的输入和输出相配对的数据，让计算机从中学习出规律，从而能针对一个新的输入做出合理的输出预测。例如，识别信封上手写的邮政编码，基于医学影像判断肿瘤是否为良性，检测信用卡交易中的诈骗行为。

- 回归学习：预测模型的输出是一个连续的函数。

- 分类学习：输出结果是离散的。

一些回归算法也可以用来进行分类，反之亦然。

- 无监督学习：通过学习大量的无标记的数据，去分析出数据本身的内在特点和结构。一个非常重要的非监督任务是异常检测。异常检测的系统使用正常值训练，当碰到一个新实例，它可以判断这个新实例是正常值还是异常值。例如，检测异常的信用卡转账以防欺诈，检测制造缺陷等。又如，确定一系列博客文章的主题，将客户分成具有相似偏好的群组，检测网站的异常访问模式。

- 聚类：从数据中去分析数据的类型。

分类问题是在已知答案里选择一个，聚类问题的答案是未知的，需要从数据中挖掘出来。

- 半监督学习：多数半监督学习算法是非监督和监督算法的结合，一些算法可以处理部分带标签的训练数据，通常是大量不带标签数据加上小部分带标签数据。

- 强化学习：学习系统在这里被称为智能体，可以对环境进行观察、选择和执行动作，并获得奖励作为回报。然后它必须自己学习哪个是最佳方法，称为策略，以得到长久的最大奖励。策略决定了智能体在给定情况下应该采取的行动。例如，许多机器人进行强化学习算法以学习如何行走，AlphaGo通过分析数百万盘棋局学习制胜策略，然后自己和自己下棋。注意的是，在比赛中中机器学习是关闭的，AlphaGo只是使用它学会的策略。

- 机器学习应用开发的典型步骤

    样本，每个实体或每一行数据；每一列称为特征；如何构建良好的数据表征，称为特征提取或特征工程。

    1.数据采集和标记（训练样本，特征，数据标记）

    2.数据清洗：归一化过程

    3.特征选择

    4.模型选择

    5.模型训练和测试（训练数据集，测试数据集，交叉验证数据集）

    6.模型性能评估和优化

    7.模型使用

### 贝叶斯分类器

贝叶斯分类是一类分类算法的总称，这类算法均以贝叶斯定理为基础，故统称为贝叶斯分类，主要分类有高斯贝叶斯分类器、半朴素贝叶斯分类器、朴素贝叶斯分类器等。而朴素朴素贝叶斯分类是贝叶斯分类中最简单，也是常见的一种分类方法。
