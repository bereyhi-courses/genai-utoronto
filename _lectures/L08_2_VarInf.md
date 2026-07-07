---
type: lecture
date: 2026-07-07T15:00:00
title: "Lecture 8 - Part 2/2: Variational Inference"
tldr: "VAE - Part II"
stat: lec
# for lectures stat: lec
description: In this lecture, we study Variational Inference. This framework enables us to develop an implicit approach for estimating the likelihood of probabilistic generators. Using that we can build a training loop for probabilistic generators utilizing the evidence lower bound (ELBO). This is the key training approach used in VAEs.
videoID: ZyBDrJmS0VM
hide_from_announcments: false
---
**Lecture Notes:**
- [Chapter 5 - Section 2]({{ site.baseurl }}/assets/Notes/CH5/CH5_Sec2.pdf)

**Further Reads:**
* [ELBO](https://www.bishopbook.com/): Chapter 16 of [[BB]](https://www.bishopbook.com/) __Section 16.3__
* [VI for Likelihood](https://arxiv.org/abs/1302.3586) The early paper _Computing Upper and Lower Bounds on Likelihoods in Intractable Networks_ published by
_T. Jaakkola and M. Jordan_ at UAI in 1996
* [Tutorials on VI](https://arxiv.org/abs/1701.00160) Review paper _Variational Inference: A Review for Statisticians_ published by
_D. Blei, A. Kucukelbir, and J. McAuliffe_ in 2016 giving a good overview on VI framework
* [Introduction to VI](https://arxiv.org/abs/1906.02691) Book _An Introduction to Variational Autoencoders_ written by _D. Kingma and M. Welling_ and published by NOW in 2019