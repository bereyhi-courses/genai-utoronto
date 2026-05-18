---
type: lecture
date: 2026-05-05T14:00:00
title: "Lecture 1: Language Modeling"
tldr: "LMs - Part 1"
stat: lec
# for lectures stat: lec
description: We start with LMs and understand how we can feed a text into it by doing the so-called "Tokenization" and "Embedding". We build simple language model called Bi-Gram and understand its limitations. This motivates us to build a context-aware LM. We look into the basic context-aware LM design via RNNs. Unfortunately, the audio recording is not good due to the issue with the recording device. 
videoID: 8EeD0Cq1hBQ 
hide_from_announcments: false
---
**Lecture Notes:**
- [Chapter 1 - Section 1]({{ site.baseurl }}/assets/Notes/CH1/CH1_Sec1.pdf) 

**Further Reads:**
* [Tokenization](https://web.stanford.edu/~jurafsky/slp3/2.pdf): Chapter 2 of [[JM]](https://web.stanford.edu/~jurafsky/slp3/)
* [Embedding](https://web.stanford.edu/~jurafsky/slp3/6.pdf): Chapter 6 of [[JM]](https://web.stanford.edu/~jurafsky/slp3/)
* [Original BPE Algorithm](http://www.pennelynn.com/Documents/CUJ/HTML/94HTML/19940045.HTM): Original BPE Algorithm proposed by Philip Gage in 1994
* [BPE for Tokenization](https://arxiv.org/abs/1508.07909): Paper _Neural machine translation of rare words with subword units_ by _Rico Sennrich, Barry Haddow, and Alexandra Birch_ presented in ACL 2016 that adapted BPE for NLP
* [LMs](https://www.bishopbook.com/): Chapter 12 of [[BB]](https://www.bishopbook.com/) __Section 12.2__
* [N-Gram LMs](https://web.stanford.edu/~jurafsky/slp3/3.pdf): Chapter 3 of _Speech and Language Processing;_ __Section 3.1__ on N-gram LM
* [Maximum Likelihood](https://www.bishopbook.com/): Chapter 2 of [[BB]](https://www.bishopbook.com/) __Sections 2.1 -- 2.3__
* [Recurrent LMs](https://web.stanford.edu/~jurafsky/slp3/8.pdf): Chapter 8 of [[JM]](https://web.stanford.edu/~jurafsky/slp3/)
* [LSTM LMs](https://arxiv.org/abs/1708.02182): Paper _Regularizing and Optimizing LSTM Language Models_ by _Stephen Merity, Nitish Shirish Keskar, and Richard Socher_ published in ICLR 2018 enabling LSTMs to perform strongly on word-level language modeling
* [High-Rank Recurrent LMs](https://arxiv.org/abs/1711.03953): Paper _Breaking the Softmax Bottleneck: A High-Rank RNN Language Model_ by _Zhilin Yang, Zihang Dai, Ruslan Salakhutdinov, and William W. Cohen_ presented at ICLR 2018 proposing Mixture of Softmaxes (MoS) and achieving state-of-the-art results at the time