# 最优化算法-2024秋
<img src="qp.png" style="zoom:80%;" align="right"/>

最优化算法是人工智能、数据科学等相关领域的必修课程。
本课程从优化问题的建模出发，主要介绍不同优化模型的求解思想，求解算法，也兼顾对基本的优化理论学习。
课程内容包括了连续和离散优化，以无约束优化，线性规划和整数优化为重点内容。
本课程亦可是学生未来学习数据和决策分析等的高级技术的基础。

# 大纲


1. 一维无约束优化
    - Goldsection, 斐波那契法，二分法
    - 牛顿法，割线法，二次拟合法
1. 多维优化基础
    - 线性代数和矩阵基础：二次型，正定矩阵，范数等
    - 梯度
    - 黑塞矩阵    
1. 多维无约束规划-案例及最优性条件
    - 案例：统计几种回归
    - 最优性条件
    - 下降法，Wolf近似条件
    - 梯度法，共轭法
    - 牛顿法，拟牛顿法
1. 有约束规划
    - 案例：SVM分类
    - 拉格朗日对偶、最优性条件-KKT， 
    - 线性约束：投影法
    - 外点法，内点法
1. 线性规划
    - 案例：调度、线性回归等
    - 单纯形法
    - 对偶问题及对偶性质
    - 对偶单纯形(optional)    
1. 整数规划
    - 案例:选址问题，旅行商问题
    - 线性松弛、完全幺模矩阵、网络流.
    - Rounding和其他算法
    - Gomory割平面法
    - 分支定界    
1. 全局搜索
    - 随机搜索
    - 模拟退火
    - 粒子群算法
    - 遗传算法

# 课程要求
基本的微积分和线性代数基础；
最好会一门编程语言。

# 教学ppt

| 日期 | 课程内容     | 课堂PPT | 作业下载 | 
| -----------| ----------- | ----------- |----------- |
|2024年9月2日 | 绪论        | [PPT](https://1drv.ms/b/s!Ah-FtUlVkbCKnWJJQ2kJw4XtSZw_?e=W0FFgn)| 无 |
|2024年9月4日 | 24ch02-1-简单优化问题-一维搜索-不可导| [PPT](https://1drv.ms/b/s!Ah-FtUlVkbCKnXacijl2UG4qEYiX?e=tzSev6) | 无 |
|2024年9月9日 | 24ch02-2-简单优化问题-一维搜索-可导 | [PPT](https://1drv.ms/b/s!Ah-FtUlVkbCKnXloQIb5mH9uf2Wk?e=Y8JeYI) | 习题：教科书P88-P89页： 7.1, 7.2-b,c, 7.7, 7.9 |
|2024年9月11日 | 24ch03-1-基础知识-多维函数概念  | [PPT](https://1drv.ms/b/s!Ah-FtUlVkbCKnhd9oxzlVKBHPVCl?e=WI9C6e) | 无 |
|2024年9月14日(按照9.16周一上课) | 24ch03-2-基础知识-凸集、凸函数和凸优化  | [PPT](https://1drv.ms/b/s!Ah-FtUlVkbCKnhuwTw3MiD1bLVOe?e=xqeJlz) | 习题：教科书P369, 22.6, 22.8, 22.20 |
|2024年9月18日 | 24ch04-1-无约束规划-案例及最优性条件 | [PPT](https://1drv.ms/b/s!Ah-FtUlVkbCKnjVcQ41Q2-woxQv8?e=Dka74m) | 习题：教科书P65, 6.8, 6.9, 6.30 |
|2024年9月18日-23日 | 24ch04-2-无约束规划-下降法 | [PPT](https://1drv.ms/b/s!Ah-FtUlVkbCKnjYBJMf8wkuhBiP3?e=B5m6fn) | 无 |
|2024年9月23日 | 24ch04-3-无约束规划-一阶方法-梯度 + 共轭法 | 共轭法[PPT](https://1drv.ms/b/c/8ab0915549b5851f/ER-FtUlVkbAggIqEDwAAAAABoRE-_dpABjEx-RqBRoaWUg?e=bzZyAh) | 习题：教科书8.1，8.8，8.16, 10.5,10.7,10.9 |
|2024年9月25日 | 24ch04-4-无约束规划- 牛顿法 | 牛顿法[PPT](https://1drv.ms/b/c/8ab0915549b5851f/ER-FtUlVkbAggIqFDwAAAAABf3n_2SVhHBSYfH01BoaVFw?e=3CMd5f) | 无 |
|2024年9月30日 | 24ch04-4-无约束规划-拟牛顿法1 | 拟牛顿法[PPT](https://1drv.ms/b/c/8ab0915549b5851f/ER-FtUlVkbAggIqGDwAAAAABXm1ew4_0VJdBGbENnugL4w?e=KMpkNv) | 无 |
|2024年10月9日 | 24ch04-4-拟牛顿法 2 | -- | 无 |
|2024年10月12日 （按照国庆假期10.7日周一上课）| 24ch05-1-有约束规划-案例, SVM  |[PPT](https://1drv.ms/b/c/8ab0915549b5851f/EcFhUQPTaQpFmIvjIzGPnKABFQ8SCPu5qF4oT-v5LfIwuQ?e=zA5A6o) | 无 |
|2024年10月14日 | 24ch05-2-有约束优化-拉格朗日对偶，等式约束的一阶最优性条件 | 拉格朗日对偶,等式约束一阶必要条件，KKT等，[PPT](https://1drv.ms/b/c/8ab0915549b5851f/EXvFukdGKfxCuVF4DBtbZ-gBWekxmGW5ArqGt-9UsJAiUQ?e=4croYc) | 无 |
|2024年10月16日 | 有约束优化-KKT条件 |--  | 无 |
|2024年10月21-22日 | （调课）无课程 |--  | 无 |
|2024年10月28日 | 有约束优化算法，投影法，罚函数法 |[PPT](https://1drv.ms/b/c/8ab0915549b5851f/ETyWBN5HOjRAttFV9b5muAIBYJczoo14PVSWzFEgB8YVKw?e=TynooF)  | 无 |
|2024年10月30日 | 有约束优化算法内点法，习题课1 |--| 无 |
|2024年11月4日 | 习题课2， 线性优化案例介绍 |[PPT](https://1drv.ms/b/c/8ab0915549b5851f/EcFhUQPTaQpFmIvjIzGPnKABcFVF7Td_W35PktM9TNr0yA?e=bRcTeY)  | 无 |
|2024年11月6日 | 线性优化基本概念 |[PPT](https://1drv.ms/b/c/8ab0915549b5851f/EbPCvWNvwfhMhkT4mvdKEO8BKbZCUjs5Qo6hE5F4qhwrOg?e=k6gzvL)  | 无 |
|2024年11月11日-11月13日 | 线性优化-单纯形法，二阶段|[PPT](https://1drv.ms/b/c/8ab0915549b5851f/Eb2WVgoVsLFOtMfOz8QgsA8BsDSa4O9IeDsO4TZ9DkOCeQ?e=c5xjlC)  | 无 |
|2024年11月18日 | 线性优化-对偶|[PPT](https://1drv.ms/b/c/8ab0915549b5851f/EbItmE6HbApBmnnNyhEFISMB6Ia9JXAyLGt4Xm9o8K9Idg?e=ec1OLf) | 无 |
|2024年11月20日 | 对偶单纯形*，线性规划求解器| [PPT](https://1drv.ms/b/c/8ab0915549b5851f/EaNOV-iLnvFGhTmGq8aL5jQB448MX7pbwSBNzNj6zk8w_A?e=wtlzez) |习题：教科书15.1,15.5,16.3,16.4,16.9,17.4,17.6,17.15|
|2024年11月25日 | 整数规划基础|[PPT](https://1drv.ms/b/c/8ab0915549b5851f/EePr05r6n5ZJtarq13R93S4BCn2uJZXfsLsXPDMV3cY2kw?e=mHPBRj) |无|
|2024年11月27日 | Gomory切平面| [PPT](https://1drv.ms/b/c/8ab0915549b5851f/EVK6L1Dh6NBAs8lz61EjlEkBth8cn4TZlmPt7mPMvTaMIQ?e=TLtkdX) |无|
|2024年12月2日 | 分支定界法| [PPT](https://1drv.ms/b/c/8ab0915549b5851f/EaMq89YioYJPmnc0B6gLn44BF1I6U2jgQ2MIq8id1rSt4Q?e=SksuYC) |无|
|2024年12月2日 | 全局搜索算法（启发式），复习课| [PPT](https://1drv.ms/b/c/8ab0915549b5851f/Ea29Yl15MmNCujTeS-qd13YBvIbfiYG377cQ_1NzXSFH9A?e=fXIq6Q) |无|




# 课程答疑
一般情况下，助教会在群内回复各位同学的疑问。任课老师会根据助教反馈将大家都存在的问题在课堂上解释。
教师办公室：科研4号楼545


# 课程资源
- [南京大学，最优化理论与方法](https://www.icourse163.org/course/NJU-1465971171?from=searchPage&outVendor=zw_mooc_pcssjg_)
- 在线书籍，Julia代码[Algorithms for Optimization](https://mitpress.mit.edu/9780262039420/algorithms-for-optimization/)
- pyomo: 基于python开源优化建模语言 https://www.pyomo.org/
