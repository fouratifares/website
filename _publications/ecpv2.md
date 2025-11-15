---
title: "ECPv2: Fast, Efficient, and Scalable Global Optimization of Lipschitz Functions"
collection: publications
permalink: /publication/ecpv2
date: 2026-02-20
venue: 'Proceedings of the AAAI Conference on Artificial Intelligence'

[//]: # (paperurl: 'https://arxiv.org/abs/2502.04290')
---
Fares Fourati, Mohamed-Slim Alouini, & Vaneet Aggarwal

[[Abstract]](C:\Users\FOURATF\Desktop\faresfourati.github.io\files\ECPv2_appendix.pdf), [[Code]](https://github.com/fouratifares/ECP/tree/main)

## Abstract
We propose ECPv2, a scalable and theoretically grounded algorithm for global optimization of Lipschitz-continuous functions with unknown Lipschitz constants. Building on Every Call is Precious (ECP) framework, which ensures that each accepted function evaluation is potentially informative, ECPv2 addresses key limitations of ECP, including high computational cost and overly conservative early behavior. ECPv2 introduces three innovations: (i) an adaptive lower bound to avoid vacuous acceptance regions, (ii) a Worst-$m$ memory mechanism that restricts comparisons to a fixed-size subset of past evaluations, and (iii) a fixed random projection to accelerate distance computations in high dimensions. We theoretically show that ECPv2 retains ECP’s no-regret guarantees with optimal finite-time bounds and expands the acceptance region with high probability. We further empirically validate these findings through extensive experiments and ablation studies. Using principled hyperparameter settings, we evaluate ECPv2 across a wide range of high-dimensional, non-convex optimization problems. Across benchmarks, ECPv2 consistently matches or outperforms state-of-the-art optimizers, while significantly reducing wall-clock time.

<img src="C:\Users\FOURATF\Desktop\faresfourati.github.io\images\surface_plot.png" width="700" height="200"/>