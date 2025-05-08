---
layout: page
title: Materials
permalink: /materials/
---

## Lecture Notes
The lecture notes are uploaded through the semester. For each chapter, the notes are provided section by section. 
### Chapter 0: Course Overview and Logistics
* [Handouts]({{site.baseurl}}/assets/Notes/CH0/CH0.pdf): All Sections included in a single file

### Chapter 1: Text Generation via Language Models
* [Section 1]({{site.baseurl}}/assets/Notes/CH1/CH1_Sec1.pdf): Fundamentals of Language Modeling - Primary LMs
* [Section 2]({{site.baseurl}}/assets/Notes/CH1/CH1_Sec2.pdf): Transform-based Models

## Book

There is indeed no single textbook for this course, and we use various resources in the course. Most of resources are research papers, which are included in the reading list below and completed through the semester. The following textbooks have however covered some key notions and related topics. 

* [[BB] Bishop, Christopher M., and Hugh Bishop. _Deep Learning: Foundations and Concepts._ Springer Nature, 2023.](https://www.bishopbook.com/)
* [[M] Murphy, Kevin P. _Probabilistic Machine Learning: Advanced Topics._ MIT Press, 2023.](https://probml.github.io/pml-book/book2.html)
* [[GYC] Goodfellow, Ian, et al. _Deep Learning._ MIT Press, 2016.](https://www.deeplearningbook.org/)

With respect to the first part of the course, the following book provides some good read:

* [[JM]Jurafsky, Dan, and James H. Martin. _Speech and Language Processing._ 3rd Edition, 2024.](https://web.stanford.edu/~jurafsky/slp3/)

The following recent textbooks are also good resources for __practicing hands-on skills.__ Note that we are __not__ simply learning to implement only! We study the fundamentals that led to development of this framework, nowadays known as __generative AI.__ Of course, we try to get our hands dirty as well and learn how to do implementation.

* [Sanseviero, Omar, et al. _Hands-On Generative AI with Transformers and Diffusion Models._ O'Reilly Media, Inc., 2024.](https://www.oreilly.com/library/view/hands-on-generative-ai/9781098149239/)
* [Alammar, Jay, and Maarten Grootendorst. _Hands-on large language models: language understanding and generation._ O'Reilly Media, Inc., 2024.](https://www.oreilly.com/library/view/hands-on-large-language/9781098150952/)


## Reading List

This section will be completed gradually through the semseter. I will try to break down the essence of each item, so that you could go over them easily. 

### Review
You may review the idea of Seq2Seq learning in the following references:
* [SimpleLM](https://pdfs.semanticscholar.org/bba8/a2c9b9121e7c78e91ea2a68630e77c0ad20f.pdf): Initial ideas on making a language model
* [SeqGen](https://arxiv.org/abs/1308.0850): Sequence generation via RNNs --_Old idea, but yet worth thinking about it!_
* [Seq2Seq](https://arxiv.org/abs/1409.3215v3): How we can do sequence to sequence learning via NNs

You may review the idea of transformers in the following resources:
* [Transformer Paper](https://arxiv.org/abs/1706.03762): Paper __Attention Is All You Need!__ published in 2017 that made a great turn in sequence processing
* [Transformers](https://web.stanford.edu/~jurafsky/slp3/9.pdf): Chapter 9 of [[JM]](https://web.stanford.edu/~jurafsky/slp3/)
* [Transformers](https://www.bishopbook.com/): Chapter 12 of [[BB]](https://www.bishopbook.com/) __Section 12.1__

### Chapter 1: Text Generation and Language Models
#### Tokenization and Embedding
* [Tokenization](https://web.stanford.edu/~jurafsky/slp3/2.pdf): Chapter 2 of [[JM]](https://web.stanford.edu/~jurafsky/slp3/)
* [Embedding](https://web.stanford.edu/~jurafsky/slp3/6.pdf): Chapter 6 of [[JM]](https://web.stanford.edu/~jurafsky/slp3/)


* [Original BPE Algorithm](http://www.pennelynn.com/Documents/CUJ/HTML/94HTML/19940045.HTM): Original BPE Algorithm proposed by Philip Gage in 1994
* [BPE for Tokenization](https://arxiv.org/abs/1508.07909): Paper _Neural machine translation of rare words with subword units_ by _Rico Sennrich, Barry Haddow, and Alexandra Birch_ presented in ACL 2016 that adapted BPE for NLP
* [SentencePiece](https://arxiv.org/abs/1808.06226): Paper _SentencePiece: A simple and language independent subword tokenizer and detokenizer for Neural Text Processing_ by _Taku Kudo and John Richardson_ presented in EMNLP 2018 that introduces a language-independent tokenizer
* [WordPiece](https://arxiv.org/abs/1609.08144): Paper _Google’s Neural Machine Translation System: Bridging the Gap between Human and Machine Translation_ by _Yonghui Wu et al._ published in 2016 introducing WordPiece (used in BERT)
* [ByT5](https://arxiv.org/abs/2105.13626): Paper _ByT5: Towards a token-free future with pre-trained byte-to-byte models_ by _Xue et al._ presented in ACL 2022 proposing ByT5

#### Language Modelling
* [LMs](https://www.bishopbook.com/): Chapter 12 of [[BB]](https://www.bishopbook.com/) __Section 12.2__
* [N-Gram LMs](https://web.stanford.edu/~jurafsky/slp3/3.pdf): Chapter 3 of _Speech and Language Processing;_ __Section 3.1__ on N-gram LM
* [Maximum Likelihood](https://www.bishopbook.com/): Chapter 2 of [[BB]](https://www.bishopbook.com/) __Sections 12.1 -- 12.3__

#### Recurrent LMs
* [Recurrent LMs](https://web.stanford.edu/~jurafsky/slp3/8.pdf): Chapter 8 of [[JM]](https://web.stanford.edu/~jurafsky/slp3/)
* [LSTM LMs](https://arxiv.org/abs/1708.02182): Paper _Regularizing and Optimizing LSTM Language Models_ by _Stephen Merity, Nitish Shirish Keskar, and Richard Socher_ published in ICLR 2018 enabling LSTMs to perform strongly on word-level language modeling
* [High-Rank Recurrent LMs](https://arxiv.org/abs/1711.03953): Paper _Breaking the Softmax Bottleneck: A High-Rank RNN Language Model_ by _Zhilin Yang, Zihang Dai, Ruslan Salakhutdinov, and William W. Cohen_ presented at ICLR 2018 proposing Mixture of Softmaxes (MoS) and achieving state-of-the-art results at the time


#### Transformer-based LMs
* [Transformer LMs](https://www.bishopbook.com/): Chapter 12 of [[BB]](https://www.bishopbook.com/) __Section 12.3__
* [LLMs via Transformers](https://web.stanford.edu/~jurafsky/slp3/10.pdf): Chapter 10 of [[JM]](https://web.stanford.edu/~jurafsky/slp3/)

#### LLMs
* [BERT](https://arxiv.org/abs/1810.04805): Paper _BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding_ by _Jacob Devlin et al._ presented at NAACL 2019 that introduced BERT
<!-- * [XLNet: Generalized Autoregressive Pretraining for Language Understanding](https://arxiv.org/abs/1906.08237): Paper _XLNet: Generalized Autoregressive Pretraining for Language Understanding_ by _Zhilin Yang et al._ presented at NeurIPS 2019 that introduces XLNet -->
* [RoBERTa](https://arxiv.org/abs/1907.11692): Paper _RoBERTa: A Robustly Optimized BERT Pretraining Approach_ by _Yinhan Liu, et al._ (Facebook AI, 2019) that shows BERT's performance can be significantly improved by more data, longer training, and removing next sentence prediction
* [T5](https://arxiv.org/abs/1910.10683): Paper _Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer_ by _Colin Raffel et al._ (JMLR 2020) that reformulates all NLP tasks as text-to-text problems introducing the T5 model


* [GPT-1](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf): Paper _Improving Language Understanding by Generative Pre-Training_ by _Alec Radford et al._ (OpenAI, 2018) that introduced GPT-1 and revived the idea of pretraining transformers as LMs followed by supervised fine-tuning
* [GPT-2](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf): Paper _Language Models are Unsupervised Multitask Learners_ by _Alec Radford et al._ (OpenAI, 2019) that introduces GPT-2 with 1.5B parameter trained on web text
* [GPT-3](https://arxiv.org/abs/2005.14165): Paper _Language Models are Few-Shot Learners_ by _Tom B. Brown et al._ (OpenAI, 2020) that introduces GPT-3, a 175B-parameter transformer LM 
* [GPT-4](https://arxiv.org/abs/2303.08774): _GPT-4 Technical Report_ by _OpenAI_ (2023) that provides an overview of GPT-4’s capabilities

