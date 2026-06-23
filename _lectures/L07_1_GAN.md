---
type: lecture
date: 2026-06-23T13:00:00
title: "Lecture 7 - Part 1/2: Generative Adversarial Nets"
tldr: "GANs - Part I"
stat: lec
# for lectures stat: lec
description: (Unfortunately, the recording did not work, so this is an older recording from last year.) We start with GANs. We see that though looking like a flow model, they are unable to use direct MLE due to challenges involved in likelihood computation. We then intuitively discuss adversarial mechanism used to train the generator. We see how we can train it by implementing a min-max game. We discuss its training and sampling. We see how GAN training can be interpreted as an implicit maximum-likelihood learning. This will serve us as a background to understand how Wasserstein GAN is working. 
videoID: k5KLueu6-D4 
hide_from_announcments: false
---
**Lecture Notes:**
- [Chapter 4 - Section 1]({{ site.baseurl }}/assets/Notes/CH4/CH4_Sec1.pdf)
- [Chapter 4 - Section 2]({{ site.baseurl }}/assets/Notes/CH4/CH4_Sec2.pdf)

**Further Reads:**
* [Tutorial on GANs](https://arxiv.org/abs/1701.00160) Tutorial _Generative Adversarial Networks_ given by _I. Goodfellow_ at NeurIPS in 2016
* [GANs](https://proceedings.neurips.cc/paper_files/paper/2014/hash/f033ed80deb0234979a61f95710dbe25-Abstract.html) Paper _Generative Adversarial Nets_ published by _I. Goodfellow et al._ at NeurIPS in 2014 proposing GANs 