# proj282-Intelligent-Compute-Runtime-Library
## 标题
面向智能计算的运行时库优化开发

## 项目描述

随着数据和信息的不断增长，社会生产生活越来越离不开智能软件的支持。然而，智能计算一般有着巨大的算力需求。一方面，多样化的智能应用需要多元化的算力，算力已经成为人工智能继续发展的重中之重；另一方面，从计算资源到算力的转化依然存在巨大鸿沟，算力的效能并未得到充分释放。提高算力的效能需要多方面的优化和配合，实验和应用发现，智能计算效能的发挥在不同的硬件平台和基础软件层之上有巨大的差别，在计算的基础设施方面针对智能计算有着巨大的优化空间和迫切要求。

操作系统（Operating System，OS）是管理计算机硬件与软件资源的计算机程序，作为核心总控软件，其功能包括屏蔽复杂的接口，简化程序员和用户的使用，达成应用程序对硬件的多路复用，实施各种计算资源的高效分配和利用，隔离外界的非法操作并保护资源等。操作系统对计算系统的性能有决定性影响，堪称计算机系统的灵魂。我国在进入新世纪后，一直把操作系统放在具有基础性、战略性、前瞻性和重大关键共性软件技术的第一位，并作为十三五构建现代信息技术和产业生态体系的主要环节。

虽然操作系统仍对智能软件的运行提供了基础关键服务，但为了简化智能应用的开发，匹配智能计算的数据流驱动模型，智能计算往往是构建在智能计算框架服务之上的，并同操作系统之间产生了某种隔阂。在AI框架的包装下，操作系统很难直接参与智能计算的资源分配与算子任务的调度，因此产生了严重的信息不透明。一方面，操作系统并不清楚资源申请方的依赖性或者互斥性，在进行内存或处理线程分配时难以避免冲突的发生；另一方面AI框架不了解底层硬件平台的特性，无法面向硬件实现计算资源使用的优化。

当前大多数针对智能计算优化的研究大都集中在AI框架本身，操作系统无法针对AI作业特性做出优化，使AI作业在不同硬件平台上呈现出巨大的性能差异。为此，本项目的目的打通AI框架同操作系统资源管理隔阂的思路，研究操作系统对于AI计算的内核服务优化机制和策略，从而避免用户根据不同硬件平台分别对AI框架做专家级优化。

## 预期目标

- 使操作系统能直接参与到AI计算的运行时优化；
- 使AI框架能够感知硬件平台特性；

## 特征

- 在不同的硬件平台上，尤其是国产众核处理器平台等复杂硬件平台上，如FT2000+，展现释放算力效能的效果
- 在OpenKylin操作系统上实现适配
- 文档、代码、问题、答疑交互过程都开放和开源的

## 已有参考资料

- Mohammad Dashti;Alexandra Fedorova;Justin Funston;Fabien Gaud;Renaud Lachaize;Baptiste Lepers;Vivien Quema;Mark Roth.Traffic Management: A Holistic Approach to Memory Placement on NUMA Systems[A].ASPLOS'13: Proceedings of the eighteenth international conference on Architectural support for programming languages and operating systems[C],2013
- François Broquedis ;Nathalie Furmento ;Brice Goglin ;Pierre-André Wacrenier ;Raymond Namyst .ForestGOMP: An Efficient OpenMP Environment for NUMA Architectures.[J].International Journal of Parallel Programming,2010,Vol.38(5): 418-439 
- Dongsheng Li;Dan Huang;Zhiguang Chen;Yutong Lu.Optimizing Massively Parallel Winograd Convolution on ARM Processor[A].ICPP '21: Proceedings of the 50th International Conference on Parallel Processing[C],2021 

## 赛题分类

未归类运行时支撑

## 参赛要求

- 以小组为单位参赛，最多四人一个小组，且小组成员是来自同一所高校的本科生或研究生
- 允许学生参加大赛的多个不同题目，最终自己选择一个题目参与评奖
- 请遵循“2024全国大学生操作系统比赛”的章程和技术方案要求

## 难度

中等

## License

GPL-3.0 License

## 所属赛道

2024全国大学生操作系统比赛的“OS功能挑战”赛道

## 项目导师

- 姓名：董攀
- 单位：国防科技大学
- github ID：https://github.com/pandong
- email：pandong@nudt.edu.cn
