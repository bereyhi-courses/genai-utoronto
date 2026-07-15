---
type: lecture
date: 2026-07-14T15:00:00
title: "Lecture 9 - Part 2/3: Training Loop for VAEs"
tldr: "VAE - Part II"
stat: lec
# for lectures stat: lec
description: In this lecture, we complete the training loop for a computational VAE. We see that for this, we need to compute the gradient on a stochastic computation graph. We can do this using Importance Sampling or Reparameterization trick. 
videoID:  
hide_from_announcments: false
---
**Lecture Notes:**
- [Chapter 5 - Section 3]({{ site.baseurl }}/assets/Notes/CH5/CH5_Sec3.pdf)

**Further Reads:**
* [DCVAE](https://arxiv.org/abs/1312.6114) Paper _Semi-Supervised Learning with Deep Generative Models_ published by _D. Kingma et al._ in 2014 implementing a Deep Convolutional VAE
* [Transformer VAE](https://ieeexplore.ieee.org/abstract/document/9054554) Paper _Transformer VAE: A Hierarchical Model for Structure-Aware and Interpretable Music Representation Learning_ published by _J. Jiang et al_ in ICASSP 2020 proposing a Transformer based VAE
* [VAE with VampPrior](https://arxiv.org/abs/1705.07120) Paper _VAE with a VampPrior_ published by _J. Tomczak and M. Welling_ in 2017 proposing VAE with general latent prior