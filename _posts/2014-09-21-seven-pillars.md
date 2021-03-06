---
layout: post
title: 统计学的七大支柱
---

JSM上统计界的老帮主Stephen Stigler做了一个主题演讲，讲[“统计学的七大支柱”](http://blogs.sas.com/content/iml/2014/08/05/stiglers-seven-pillars-of-statistical-wisdom/)，好心又认真的Rick Wicklin同学记了笔记，彼时估计还在中国城吃饭的我才得以了解SS大人到底讲了什么。回头看看笔记，我觉得SS大人有点吹嘘统计学之嫌。所谓支柱，就是没了它咱就垮了。七大支柱为：

1. 汇总：我们从数据汇总中获得知识。本小子认为汇总是统计的经典用途，但汇总（描述统计）只是统计学的一方面，另一个同样重要也相对更靠谱一些的方面是预测。我从来都是扬预测而抑汇总的，因为统计学生来就带有不靠谱的本性，汇总搞错了无从查证，预测错了一定程度上我们还是知道错了多远的。
2. 边际效应递减：随着数据量增大，信息量并不是线性增加，而是到了一定程度之后可能就没太多新的信息了。SS大人用n（样本量）的平方根来形容这个递减，我觉得太牵强了，例如样本均值的标准误里有个n的平方根，但这跟信息有毛线关系呢？
3. 似然/概率：概率论当然是统计学的支柱，当然也要取决于我们怎么定义统计学，但说概率是数理统计的基础肯定不会有人不同意。有人说统计是“研究不确定性的科学”，我现在最烦的就是“科学”二字，人人都把自己的工作升级为科学，尼玛什么是科学？我认为数学/数理统计可以是学科，但不是科学。要称自己的做的是科学，先问问那些养兔子和大肠杆菌的苦逼博士们再想想自己做的算不算科学。说自己研究的是一门学科又没什么丢人的，这年头神马“数据科学”，以及孟生旺老师讽刺的“数学科学学院”（一个名字里三个重复的字，直接叫“数学系”丢人吗？），都是一些没有底气的人才想出来的名词。我敬佩老老实实做实验的自然科学工作者，不是说用纸笔推公式的工作者做的是无意义的事情或者不苦逼，而是说没事不要在这些称谓上较劲，安分守己一点比较好。
4. 横向比较：例如比较两样本均值的差异。SS大人讲别的学科是与“金标准”进行比较，而我们是在数据内部比较，如方差分析ANOVA和t检验。我没太明白这算什么支柱，而且统计里面也不是没有和“金标准”比较的情形啊。
5. 回归和多元分析：身高的回归是经典例子了，这确实是一个有趣的发现，但现实中回归被用来做什么了呢？我感觉回归的主要作用是被铺天盖地的论文拿来当炮灰（你看，俺的方法比回归好），或者在外专业里面当万精油（你看，俺跑了个回归，系数显著耶）。与其说某种方法是支柱，不如说方法和领域知识的结合是支柱。没有具体的领域知识，跑个系数显著的回归只是盲人摸象。
6. 试验设计：这个当然也很重要，我觉得这是七大支柱里唯一可以称为支柱的一个，因为它可以脱离领域知识而有效。没有比较就没有鉴别，大家都知道要比较，但怎么比是个关键问题。例如前些日子火爆的汉字听写大赛就违反了“随机”、“重复”、“对照”等试验设计基本原则，在缺乏概率指导下的竞赛，难免有些不公平。
7. 模型和残差：这个有点局限于回归套路了，不是所有模型都涉及残差项的。若不检查残差的分布，统计学会不会垮掉？我认为未必。即使残差仍然有明显的特征，模型也未必完全不合适，这要看你想要获取模型中哪部分的信息。

以本小子这点微薄功底去议论老前辈的演讲，可能会让同行笑话，而且作为做过若干报告的本小子，也深知50分钟演讲往往容易让听众产生各种误解。不能以貌取人，同样也不能以某个演讲取人。在台上讲话和在台下聊天的区别还是很大的，台上未必能说出所有你计划说的话，而即使是说出来的话，也未必是你真的想表达的意思。我的信息渠道已经是二手资料了，所以很可能对SS老爷子有所不公平，但刨去这么一个老前辈名号，仅就RW同学的笔记来说，本小子的看法就是酱了。
