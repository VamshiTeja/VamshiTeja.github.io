---
title: "Submodular Batch Selection for Training Deep Neural Networks"
collection: publications
permalink: /publications/SMDL
venue: "IJCAI"
date: 2019-8-10
citation: 'K J, Joseph and <b>Vamshi Teja, R</b> and Krishnakant, Singh and Vineeth, N Balasubramanian. <i>Proceedings of the Twenty-Eighth International Joint Conference on Artificial Intelligence, IJCAI, Macao, China.</i>'
---
[[ArXiv]](https://arxiv.org/abs/1906.08771) [[Code]](https://github.com/VamshiTeja/SMDL)


## Abstract
Mini-batch gradient descent based methods are the de facto algorithms for training neural network architectures today. We introduce a mini-batch selection strategy based on submodular function maximization. Our novel submodular formulation captures the informativeness of each sample and diversity of the whole subset. We design an efficient, greedy algorithm which can give high-quality solutions to this NP-hard combinatorial optimization problem. Our extensive experiments on standard datasets show that the deep models trained using the proposed batch selection strategy provide better generalization than Stochastic Gradient Descent as well as a popular baseline sampling strategy across different learning rates, batch sizes, and distance metrics.