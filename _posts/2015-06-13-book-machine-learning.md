---
layout: post
title: "机器学习经典书籍（转）"
date: 2015-06-13 10:07:00
tag: 
categories: 机器学习
---

* content
{:toc}

原文地址(原文里面有各书籍的下载链接)：[http://www.cnblogs.com/xmphoenix/p/3683870.html](http://www.cnblogs.com/xmphoenix/p/3683870.html)


## 入门书单
《数学之美》 PDF

作者吴军大家都很熟悉。以极为通俗的语言讲述了数学在机器学习和自然语言处理等领域的应用。

《Programming Collective Intelligence》（《集体智慧编程》）PDF

作者Toby Segaran也是《BeautifulData : The Stories Behind Elegant Data Solutions》（《数据之美：解密优雅数据解决方案背后的故事》）的作者。这本书最大的优势就是里面没有理论推导和复杂的数学公式，是很不错的入门书。目前中文版已经脱销，对于有志于这个领域的人来说，英文的pdf是个不错的选择，因为后面有很多经典书的翻译都较差，只能看英文版，不如从这个入手。还有，这本书适合于快速看完，因为据评论，看完一些经典的带有数学推导的书后会发现这本书什么都没讲，只是举了很多例子而已。

《Algorithms of the Intelligent Web》（《智能web算法》）PDF

作者Haralambos Marmanis、Dmitry Babenko。这本书中的公式比《集体智慧编程》要略多一点，里面的例子多是互联网上的应用，看名字就知道。不足的地方在于里面的配套代码是BeanShell而不是python或其他。总起来说，这本书还是适合初学者，与上一本一样需要快速读完，如果读完上一本的话，这一本可以不必细看代码，了解算法主要思想就行了。

《统计学习方法》 PDF

作者李航，是国内机器学习领域的几个大家之一，曾在MSRA任高级研究员，现在华为诺亚方舟实验室。书中写了十个算法，每个算法的介绍都很干脆，直接上公式，是彻头彻尾的“干货书”。每章末尾的参考文献也方便了想深入理解算法的童鞋直接查到经典论文；本书可以与上面两本书互为辅助阅读。

《Machine Learning》（《机器学习》） PDF

作者Tom Mitchell是CMU的大师，有机器学习和半监督学习的网络课程视频。这本书是领域内翻译的较好的书籍，讲述的算法也比《统计学习方法》的范围要大很多。据评论这本书主要在于启发，讲述公式为什么成立而不是推导；不足的地方在于出版年限较早，时效性不如PRML。但有些基础的经典还是不会过时的，所以这本书现在几乎是机器学习的必读书目。

《Mining of Massive Datasets》（《大数据》） PDF

作者Anand Rajaraman[3]、Jeffrey David Ullman，Anand是Stanford的PhD。这本书介绍了很多算法，也介绍了这些算法在数据规模比较大的时候的变形。但是限于篇幅，每种算法都没有展开讲的感觉，如果想深入了解需要查其他的资料，不过这样的话对算法进行了解也足够了。还有一点不足的地方就是本书原文和翻译都有许多错误，勘误表比较长，读者要用心了。

《Data Mining: Practical Machine Learning Tools and Techniques》（《数据挖掘：实用机器学习技术》） PDF

作者Ian H. Witten 、Eibe Frank是weka的作者、新西兰怀卡托大学教授。他们的《ManagingGigabytes》[4]也是信息检索方面的经典书籍。这本书最大的特点是对weka的使用进行了介绍，但是其理论部分太单薄，作为入门书籍还可，但是，经典的入门书籍如《集体智慧编程》、《智能web算法》已经很经典，学习的话不宜读太多的入门书籍，建议只看一些上述两本书没讲到的算法。

《机器学习及其应用》

周志华、杨强主编。来源于“机器学习及其应用研讨会”的文集。该研讨会由复旦大学智能信息处理实验室发起，目前已举办了十届，国内的大牛如李航、项亮、王海峰、刘铁岩、余凯等都曾在该会议上做过讲座。这本书讲了很多机器学习前沿的具体的应用，需要有基础的才能看懂。如果想了解机器学习研究趋势的可以浏览一下这本书。关注领域内的学术会议是发现研究趋势的方法嘛。

《Managing Gigabytes》（深入搜索引擎）PDF

## 信息检索不错的书。

《Modern Information Retrieval》 PDF

Ricardo Baeza-Yates et al. 1999。貌似第一本完整讲述IR的书。可惜IR这些年进展迅猛，这本书略有些过时了。翻翻做参考还是不错的。另外，Ricardo同学现在是Yahoo Research for Europe and Latin Ameria的头头。

《推荐系统实践》 PDF

项亮，不错的入门读物

深入
《Pattern Classification》（《模式分类》第二版） PDF

作者Richard O. Duda[5]、Peter E. Hart、David。模式识别的奠基之作，但对最近呈主导地位的较好的方法SVM、Boosting方法没有介绍，被评“挂一漏万之嫌”。

《Pattern Recognition And Machine Learning》 PDF

作者Christopher M. Bishop[6]；简称PRML，侧重于概率模型，是贝叶斯方法的扛鼎之作，据评“具有强烈的工程气息，可以配合stanford 大学 Andrew Ng 教授的 Machine Learning 视频教程一起来学，效果翻倍。”

《The Elements of Statistical Learning : Data Mining, Inference, andPrediction》，（《统计学习基础：数据挖掘、推理与预测》第二版） PDF

作者RobertTibshirani、Trevor Hastie、Jerome Friedman。“这本书的作者是Boosting方法最活跃的几个研究人员，发明的Gradient Boosting提出了理解Boosting方法的新角度，极大扩展了Boosting方法的应用范围。这本书对当前最为流行的方法有比较全面深入的介绍，对工程人员参考价值也许要更大一点。另一方面，它不仅总结了已经成熟了的一些技术，而且对尚在发展中的一些议题也有简明扼要的论述。让读者充分体会到机器学习是一个仍然非常活跃的研究领域，应该会让学术研究人员也有常读常新的感受。”[7]

《Data Mining：Concepts andTechniques》（《数据挖掘：概念与技术》第三版） PDF

作者（美）Jiawei Han[8]、（加）Micheline Kamber、（加）Jian Pei，其中第一作者是华裔。本书毫无疑问是数据挖掘方面的的经典之作，不过翻译版总是被喷，没办法，大部分翻译过来的书籍都被喷，想要不吃别人嚼过的东西，就好好学习英文吧。

《AI, Modern Approach 2nd》 PDF

Peter Norvig，无争议的领域经典。

《Foundations of Statistical Natural Language Processing》 PDF

自然语言处理领域公认经典。

《Information Theory：Inference and Learning Algorithms》 PDF
《Statistical Learning Theory》 PDF

Vapnik的大作，统计学界的权威，本书将理论上升到了哲学层面，他的另一本书《The Nature ofStatistical Learning Theory》也是统计学习研究不可多得的好书，但是这两本书都比较深入，适合有一定基础的读者。

## 数学基础
《矩阵分析》 PDF

Roger Horn。矩阵分析领域无争议的经典

《概率论及其应用》 PDF

威廉·费勒。极牛的书，可数学味道太重，不适合做机器学习的

《All Of Statistics》 PDF 扫描版 PDF 高清版

机器学习这个方向，统计学也一样非常重要。推荐All of statistics，这是CMU的一本很简洁的教科书，注重概念，简化计算，简化与Machine Learning无关的概念和统计内容，可以说是很好的快速入门材料。

《Nonlinear Programming, 2nd》 PDF

最优化方法，非线性规划的参考书。

《Convex Optimization》 PDF 配套代码

Boyd的经典书籍，被引用次数超过14000次，面向实际应用，并且有配套代码，是一本不可多得的好书。

《Numerical Optimization》 PDF

第二版，Nocedal著，非常适合非数值专业的学生和工程师参考，算法流程清晰详细，原理清楚。

《Introduction to Mathematical Statistics》 PDF

第六版，Hogg著，本书介绍了概率统计的基本概念以及各种分布，以及ML，Bayesian方法等内容。

《An Introduction to Probabilistic Graphical Models》 PDF

Jordan著，本书介绍了条件独立、分解、混合、条件混合等图模型中的基本概念，对隐变量（潜在变量）也做了详细介绍，相信大家在隐马尔科夫链和用Gaussian混合模型来实现EM算法时遇到过这个概念。

《Probabilistic Graphical Models-Principles and Techniques》 PDF

Koller著，一本很厚很全面的书，理论性很强，可以作为参考书使用。

具体数学 PDF

## 经典


线性代数 (Linear Algebra)：

我想国内的大学生都会学过这门课程，但是，未必每一位老师都能贯彻它的精要。这门学科对于Learning是必备的基础，对它的透彻掌握是必不可少的。我在科大一年级的时候就学习了这门课，后来到了香港后，又重新把线性代数读了一遍，所读的是

Introduction to Linear Algebra (3rd Ed.) by Gilbert Strang.

这本书是MIT的线性代数课使用的教材，也是被很多其它大学选用的经典教材。它的难度适中，讲解清晰，重要的是对许多核心的概念讨论得比较透彻。我个人觉得，学习线性代数，最重要的不是去熟练矩阵运算和解方程的方法——这些在实际工作中MATLAB可以代劳，关键的是要深入理解几个基础而又重要的概念：子空间(Subspace)，正交(Orthogonality)，特征值和特征向量(Eigenvalues and eigenvectors)，和线性变换(Linear transform)。从我的角度看来，一本线代教科书的质量，就在于它能否给这些根本概念以足够的重视，能否把它们的联系讲清楚。Strang的这本书在这方面是做得很好的。

而且，这本书有个得天独厚的优势。书的作者长期在MIT讲授线性代数课(18.06)，课程的video在MIT的Open courseware网站上有提供。有时间的朋友可以一边看着名师授课的录像，一边对照课本学习或者复习。

http://ocw.mit.edu/OcwWeb/Mathematics/18-06Spring-2005/CourseHome/index.htm

概率和统计 (Probability and Statistics):

概率论和统计的入门教科书很多，我目前也没有特别的推荐。我在这里想介绍的是一本关于多元统计的基础教科书：

Applied Multivariate Statistical Analysis (5th Ed.) by Richard A. Johnson and Dean W. Wichern

这本书是我在刚接触向量统计的时候用于学习的，我在香港时做研究的基础就是从此打下了。实验室的一些同学也借用这本书学习向量统计。这本书没有特别追求数学上的深度，而是以通俗易懂的方式讲述主要的基本概念，读起来很舒服，内容也很实用。对于Linear regression, factor analysis, principal component analysis (PCA), and canonical component analysis (CCA)这些Learning中的基本方法也展开了初步的论述。

之后就可以进一步深入学习贝叶斯统计和Graphical models。一本理想的书是

Introduction to Graphical Models (draft version). by M. Jordan and C. Bishop.

我不知道这本书是不是已经出版了（不要和Learning in Graphical Models混淆，那是个论文集，不适合初学）。这本书从基本的贝叶斯统计模型出发一直深入到复杂的统计网络的估计和推断，深入浅出，statistical learning的许多重要方面都在此书有清楚论述和详细讲解。MIT内部可以access，至于外面，好像也是有电子版的。

分析 (Analysis)：

我想大家基本都在大学就学过微积分或者数学分析，深度和广度则随各个学校而异了。这个领域是很多学科的基础，值得推荐的教科书莫过于

Principles of Mathematical Analysis, by Walter Rudin

有点老，但是绝对经典，深入透彻。缺点就是比较艰深——这是Rudin的书的一贯风格，适合于有一定基础后回头去看。

在分析这个方向，接下来就是泛函分析(Functional Analysis)。

Introductory Functional Analysis with Applications, by Erwin Kreyszig.

适合作为泛函的基础教材，容易切入而不失全面。我特别喜欢它对于谱论和算子理论的特别关注，这对于做learning的研究是特别重要的。Rudin也有一本关于functional analysis的书，那本书在数学上可能更为深刻，但是不易于上手，所讲内容和learning的切合度不如此书。

在分析这个方向，还有一个重要的学科是测度理论(Measure theory)，但是我看过的书里面目前还没有感觉有特别值得介绍的。

拓扑 (Topology)：

在我读过的基本拓扑书各有特色，但是综合而言，我最推崇：

Topology (2nd Ed.) by James Munkres

这本书是Munkres教授长期执教MIT拓扑课的心血所凝。对于一般拓扑学(General topology)有全面介绍，而对于代数拓扑(Algebraic topology)也有适度的探讨。此书不需要特别的数学知识就可以开始学习，由浅入深，从最基本的集合论概念（很多书不屑讲这个）到Nagata-Smirnov Theorem和Tychonoff theorem等较深的定理（很多书避开了这个）都覆盖了。讲述方式思想性很强，对于很多定理，除了给出证明过程和引导你思考其背后的原理脉络，很多令人赞叹的亮点——我常读得忘却饥饿，不愿释手。很多习题很有水平。

流形理论 (Manifold theory)：

对于拓扑和分析有一定把握时，方可开始学习流形理论，否则所学只能流于浮浅。我所使用的书是

Introduction to Smooth Manifolds. by John M. Lee

虽然书名有introduction这个单词，但是实际上此书涉入很深，除了讲授了基本的manifold, tangent space, bundle, sub-manifold等，还探讨了诸如纲理论(Category theory)，德拉姆上同调(De Rham cohomology)和积分流形等一些比较高级的专题。对于李群和李代数也有相当多的讨论。行文通俗而又不失严谨，不过对某些记号方式需要熟悉一下。

虽然李群论是建基于平滑流形的概念之上，不过，也可能从矩阵出发直接学习李群和李代数——这种方法对于急需使用李群论解决问题的朋友可能更加实用。而且，对于一个问题从不同角度看待也利于加深理解。下面一本书就是这个方向的典范：

Lie Groups, Lie Algebras, and Representations: An Elementary Introduction. by Brian C. Hall

此书从开始即从矩阵切入，从代数而非几何角度引入矩阵李群的概念。并通过定义运算的方式建立exponential mapping，并就此引入李代数。这种方式比起传统的通过“左不变向量场(Left-invariant vector field)“的方式定义李代数更容易为人所接受，也更容易揭示李代数的意义。最后，也有专门的论述把这种新的定义方式和传统方式联系起来。
