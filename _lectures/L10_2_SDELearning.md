---
type: lecture
date: 2026-07-21T14:30:00
title: "Lecture 10 - Part 2/2: Score-based Diffusion"
tldr: "Diffusion - Part II"
stat: lec
# for lectures stat: lec
description: We learn about a general diffusion that is described by a SDE. We also learn how we could reverse it in time. This takes us towards more practical diffusion-based models. We design an SDE and its reverse which is able to send us from data sample to Gaussian noise and back from noise to data. We also find out what we need to learn in order to be able to get back from noise to data. We go through diffusion score matching idea which enables us to learn the required scores for data generation on a reverse SDE. This enables us to sample from data distribution via a diffusion process without learning the data score directly.
videoID: XFveIwYjz0E 
hide_from_announcments: false
---
**Lecture Notes:**
- [Chapter 6 - Section 2]({{ site.baseurl }}/assets/Notes/CH6/CH6_Sec2.pdf)

**Further Reads:**
* [Reverse-time Diffusion](https://www.sciencedirect.com/science/article/pii/0304414982900515) Paper _Reverse-time diffusion equation models_ published in Elsevier by _B. Anderson_ in 1982 esplaining the reverse-time diffusion process
* [SDE Approach](https://proceedings.neurips.cc/paper/2021/hash/0a9fdbb17feb6ccb7ec405cfb85222c4-Abstract.html) Paper _Maximum Likelihood Training of Score-Based Diffusion Models_ by _Song et al._ in NeurIPS 2021 explaining the DPM and DDPM from inverse Diffusion viewpoint
* [DSM](https://direct.mit.edu/neco/article/23/7/1661/7677/A-Connection-Between-Score-Matching-and-Denoising) Paper _Estimation of non-normalized statistical models by score matching_ published in Neural Computation by _Pascal Vincent_ in 2011 proposing the denoising approach for score estimation (DSM)
