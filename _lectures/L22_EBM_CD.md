---
type: lecture
date: 2025-06-10T18:00:00-4:00
title: "Lecture 22: MCMC - Langevin and Conservative Divergence"
tldr: "EBMs - Part 4"
stat: lec
# for lectures stat: lec
description: In this lecture, we study the Langevin Algorithm, a first-order MCMC algorithm for sampling. We learn how we can use this algorithm to develop the so-called conservative divergence approach for EBM training. This leads us to the idea of score-matching, which we will introduce briefly and leave its details for Chapter 6.
videoID: CGaS3Sxyb-M  
hide_from_announcments: false
---
**Lecture Notes:**
- [Chapter 3 - Section 4]({{ site.baseurl }}/assets/Notes/CH3/CH3_Sec4.pdf)
<!-- - [AplDL Notes: Recurent NNs]({{ site.baseurl }}/assets/AplDL/AplDL_RNNs.pdf) -->

**Further Reads:**
* [Gibbs Sampling and Langevin](https://www.bishopbook.com/): Chapter 14 of [[BB]](https://www.bishopbook.com/)
* [Conservative Divergence](https://ieeexplore.ieee.org/abstract/document/6796877) Paper _Training Products of Experts by Minimizing Contrastive Divergence,_ by _G. Hinton_ published at _Neural Computation_ in 2002 proposing the idea of _Conservative Divergence_
* [Training by MCMC](https://arxiv.org/abs/1903.08689) Paper _Implicit Generation and Generalization in Energy-Based Models_ published by _Y. Du and I. Mordatch_ in _NeurIPS_ 2019 discussing efficiency of MCMC algorithms for EBM training
* [Improved CD](https://arxiv.org/abs/1903.08689) Paper _Improved Contrastive Divergence Training of Energy-Based Models_ published by _Y. Du et al._ in _ICML_ 2021 proposing an efficient training based on Hinton's CD ideal 