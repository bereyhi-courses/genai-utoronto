---
type: lecture
date: 2026-06-09T15:00:00
title: "Lecture 5 - Part 2/2: EBMs and MCMC Algorithms"
tldr: "EBMs - Part 2"
stat: lec
# for lectures stat: lec
description: We next study the MCMC sampling, looking into Gibbs sampling and Langevin algorithms. We learn how we can use them to train an EBM. This leads ud to contrastive learning idea. We further discuss the idea of score-matching, which we will help us later on to develop Diffusion Models.
videoID: kKyMyV3f8Sk 
hide_from_announcments: false
---
**Lecture Notes:**
- [Chapter 3 - Section 3]({{ site.baseurl }}/assets/Notes/CH3/CH3_Sec3.pdf)

**Further Reads:**
* [MCMC Algorithms](https://www.bishopbook.com/): Chapter 12 of [[M]](https://probml.github.io/pml-book/book2.html) __Sections 12.3, 12.6 and 12.7__
* [Gibbs Sampling and Langevin](https://www.bishopbook.com/): Chapter 14 of [[BB]](https://www.bishopbook.com/)
* [Contrastive Divergence](https://ieeexplore.ieee.org/abstract/document/6796877) Paper _Training Products of Experts by Minimizing Contrastive Divergence,_ by _G. Hinton_ published at _Neural Computation_ in 2002 proposing the idea of _Contrastive Divergence_
* [Training by MCMC](https://arxiv.org/abs/1903.08689) Paper _Implicit Generation and Generalization in Energy-Based Models_ published by _Y. Du and I. Mordatch_ in _NeurIPS_ 2019 discussing efficiency of MCMC algorithms for EBM training
* [Improved CD](https://arxiv.org/abs/1903.08689) Paper _Improved Contrastive Divergence Training of Energy-Based Models_ published by _Y. Du et al._ in _ICML_ 2021 proposing an efficient training based on Hinton's CD ideal