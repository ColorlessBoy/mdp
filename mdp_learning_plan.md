# MDP学习计划

## MDP理论部分
1. 核心书籍: **Markov Decision Processes Discrete Stochastic Dynamic Programming**
    - 这本书的符号定义完整，并且和现在的论文所使用的符号比较接近，或者说比较被学术界接受。
    - 这本书涉及的内容比较广泛：Finite-Horizon MDP, Infinite-Horizon MDP, Discounted MDP，Continuous-Time Models等，基本涵盖了所有MDP的概念。
    - 根据目录，我大概列了一个阅读计划表。

    | Chapter No. | Chapter Title | Deadline | 
    |:-----------:|:-------------:|:--------:|
    | Ch02 | Model Formulation | 2019.07.26 |
    | Ch04 | Finite-Horizon Markov Decision Processes | 2019.08.02|
    | Ch05 | Infinite-Horizon Models: Foundations | 2019.08.09 |
    | Ch06 | Discounted Markov Decision Problems | 2019.08.16 |
    | Ch07 | The Expected Total-Reward Criterion | 2019.08.23 |
    | Ch08 | Average Reward and Related Criteria | 2019.08.30 |
    | Ch09 | The Average Reward Criterion-Multichain and Communicating Models | 2019.09.06 |
    | Ch10 | Sensitive Discount Optimality | 2019.09.13 |
    | Ch11 | Continuous-Time Models | 2019.09.20 | 
2. 辅助书籍1：**Introduction to Stochastic Dynamic Programming**
    - 这本书只有161页，阅读成本比较低。
    - 这本小册子包含了几乎所有它所用定理的证明，降低了阅读障碍。

    | Chapter No. | Chapter Title | Deadline |
    | :---------: | :-----------: | :------: |
    | Sec02 | Discounted Dynamic Programming | 2019.08.16 |
    | Sec03 | Minimizing Costs--Negative Dynamic Programming | 2019.08.23 |
    | Sec04 | Maximizing Rewards--Positive Dynamic Programming |2019.08.30 |
    | Sec05 | Average Reward Criterion | 2019.09.06 |
    | Sec06 | Stochastic Scheduling |2019.09.13 |
    | Sec07 | Bandit Process | 2019.09.20 |
3. 辅助书籍2：**Finite Markov Chains**
    - 这本书涉及的几种马尔科夫链在TD算法证明中被拿过来作为假设，例如：Absorbing MC, Regular MC。
    - 计划挑了几章来读，其他章节可能研究了MC状态转移矩阵的性质。

    | Chapter No. | Chapter Title | Deadline |
    | :---------: | :-----------: | :------: |
    | Ch03 | Absorbing Markov Chains | 2019.08.02 |
    | Ch04 | Regular Markov Chains | 2019.08.09 |
    | Ch05 | Ergodic Markov Chains | 2019.08.16 |
    
## Robust MDP
目前只找了几份论文资料。
- 论文：Action Robust Reinforcement Learning and Application in Continuous Control
- 论文：Robust Dynamic Programming
- 论文：Robust Markov Decision Process
- 书籍章节：Robust Optimization 的第十三章 Robust Markov Decision Process
- 博弈论Game Theory中的Markov Game可能和RMDP有关。


