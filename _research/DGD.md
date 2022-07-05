---
title: "Multifactorial Evolutionary Algorithm Based on Diffusion Gradient Descent"
collection: research
status: 'workingpaper'
permalink: /research/DGD
abstract: 'Multifactorial evolutionary algorithm (MFEA) is one of the most widely used evolutionary multitasking algorithms. MFEA implements knowledge transfer among optimization tasks via crossover and mutation operators, which achieves high-quality solutions more efficiently than the counterpart single-task evolutionary algorithms. MFEA has been successfully applied to various complex optimizations problems, however, there is a lack of convergence proof of the algorithm and the theoretical explanation on how the knowledge transfer can help improve the algorithm performance. To fill this gap, we propose an MFEA based on diffusion gradient descent namely MFEA-DGD in this paper. We prove the convergence of diffusion gradient descent for multiple similar tasks and show that the local convexity of some tasks can help other tasks escape from local optimums by knowledge transfer. On this theoretical foundation, we design new complementary crossover and mutation operators in MFEA-DGD, such that the evolution population has a dynamic equation similar to diffusion gradient descent, i.e., the convergence is guaranteed and the benefit from knowledge transfer is explainable. Specifically, to simulate the principle of gradient descent, the mutation operator is established based on OpenAI evolutionary strategy near the individuals. The crossover operator combines two mutated parents via a generated stochastic matrix to produce offspring. Moreover, to allow MFEA-DGD to explore more undeveloped areas, a hyper-rectangular search strategy based on opposition learning is introduced to search in the uniform search space and the subspace for each task. MFEA-DGD is verified on multi-task optimization benchmarks through a comprehensive empirical study. The experimental results show that MFEA-DGD can convergence faster to competitive results in the comparison with other state-of-the-art evolutionary multitasking algorithms. '
date: 2022-05-01
venue: 'submit at IEEE Transactions on Evolutionary Computation'
coauthors: 'Guo Li, Haili Zhang, Zhengping Liang, Zexuan Zhu'
paperurl: 'https://prestonmui.github.io/files/mui-schoefer_2021wp_alsc.pdf'
---

