---
type: lecture
date: 2025-07-17T19:30:00-4:00
title: "Lecture 48: Diffusion Score Matching"
tldr: "Diffusion by Score - Part IV"
stat: lec
# for lectures stat: lec
description: In this lecture, we go through diffusion score matching idea which enables us to learn the required scores for data generation on a reverse SDE. This enables us to sample from data distribution via a diffusion process without learning the data score.
videoID: cAWwIQoD4Lw  
hide_from_announcments: false
---
**Lecture Notes:**
- [Chapter 6 - Section 2]({{ site.baseurl }}/assets/Notes/CH6/CH6_Sec2.pdf)

**Further Reads:**
* [DSM](https://direct.mit.edu/neco/article/23/7/1661/7677/A-Connection-Between-Score-Matching-and-Denoising) Paper _Estimation of non-normalized statistical models by score matching_ published in Neural Computation by _Pascal Vincent_ in 2011 proposing the denoising approach for score estimation (DSM)
* [SDE Approach](https://proceedings.neurips.cc/paper/2021/hash/0a9fdbb17feb6ccb7ec405cfb85222c4-Abstract.html) Paper _Maximum Likelihood Training of Score-Based Diffusion Models_ by _Song et al._ in NeurIPS 2021 explaining the DPM and DDPM from inverse Diffusion viewpoint
