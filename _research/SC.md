---
title: "A Fast Distributed Screening for High-dimensional Quantile Regression"
collection: research
status: 'workingpaper'
permalink: /research/SC
abstract: 'In the era of big data, how to handle millions of sample sizes and hundreds of variables with limited memory constraints and perform variable selection is a research problem that needs to be solved. A naive divide-and-conquer approach to solve this problem is to split  the whole data into $L$ parts and run each part separately on $L$ machines, aggregating the results from all machines by averaging, and finally obtaining the selected variables. However, this tends to select more noisy variables, and the false discovery rate may not be well controlled. In this paper, we propose a data-driven screening method for high-dimensional quantile regression in distributed data to improve the method. When the number of variables is diverging, we demonstrate that the probability of selecting the true variables by this screening method tends to 1,  which can effectively reduce the dimensionality and greatly improve the computational efficiency of high-dimensional quantile regression. In addition, we demonstrate that the obtained parameter estimation errors are asymptotically normal. Finally, simulations and a real-world blog feedback example are used to evaluate the effectiveness of the proposed method.'
date: 2023-01-01
venue: 'submit at Memetic Computing'
coauthors: 'Haili Zhang, Yanlin Tang, Xuejun Jiang and Jianchen Jiang'
paperurl: 'https://ZBLSIGMA.github.io/files/fds23.pdf'
---
