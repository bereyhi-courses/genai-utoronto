---
type: lecture
date: 2025-06-03T18:00:00-4:00
title: "Lecture 18: Masked AR Models: PixelCNN and ImageGPT"
tldr: "AR Models - Part 4"
stat: lec
# for lectures stat: lec
description: This lecture goes through the idea of masked AR models. These models give us the benefit of parallel computation, and hence can be efficiently trained using Teacher-Forcing Training. We look into the examples of PixelCNN and ImageGPT: the former uses masked convolution to realize an AR model, while the latter use masked decoding.
videoID: ejqfN3OsDhk
hide_from_announcments: false
---
**Lecture Notes:**
- [Chapter 3 - Section 3]({{ site.baseurl }}/assets/Notes/CH3/CH3_Sec3.pdf)
<!-- - [AplDL Notes: Recurent NNs]({{ site.baseurl }}/assets/AplDL/AplDL_RNNs.pdf) -->

**Further Reads:**
* [PixelRNN and PixelCNN](https://arxiv.org/abs/1601.06759): Paper _Pixel Recurrent Neural Networks_ by _A. Oord et al._ presented at _ICML_ in 2016 proposing PixelRNN and PixelCNN
* [ImageGPT](https://proceedings.mlr.press/v119/chen20s/chen20s.pdf): Paper _Generative Pretraining from Pixels_ by _M. Chen et al._ presented at _ICML_ in 2020 proposing ImageGPT