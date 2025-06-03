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
* [Section 2]({{site.baseurl}}/assets/Notes/CH1/CH1_Sec2.pdf): Transformer-based LMs
* [Section 3]({{site.baseurl}}/assets/Notes/CH1/CH1_Sec3.pdf): Large Language Models

### Chapter 2: Data Generation Problem
* [Section 1]({{site.baseurl}}/assets/Notes/CH2/CH2_Sec1.pdf): Basic Definitions
* [Section 2]({{site.baseurl}}/assets/Notes/CH2/CH2_Sec2.pdf): Generative and Discriminative Learning
* [Section 3]({{site.baseurl}}/assets/Notes/CH2/CH2_Sec3.pdf): Generative Modeling

### Chapter 3: Data Generation by Explicit Distribution Learning
* [Section 1]({{site.baseurl}}/assets/Notes/CH3/CH3_Sec1.pdf): Distribution Learning
* [Section 2]({{site.baseurl}}/assets/Notes/CH3/CH3_Sec2.pdf): Autoregressive Modeling
* [Section 3]({{site.baseurl}}/assets/Notes/CH3/CH3_Sec3.pdf): Computational Autoregressive Models
* [Section 4]({{site.baseurl}}/assets/Notes/CH3/CH3_Sec4.pdf): Energy-based Models

## Tutorial Notebooks
The tutorial notebooks can be accessed below.
* [Tutorial 1]({{site.baseurl}}/assets/Tutorials/Tutorial_1.ipynb): PyTorch Overview, Batch Training, Embedding, and Tokenization, by __Amir Hossein Mobasheri__
* [Tutorial 2]({{site.baseurl}}/assets/Tutorials/Tutorial_2.ipynb): Transformers and Large Language Models, by __Amir Hossein Mobasheri__

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

#### Other Embedding Approaches
* [Word2Vec](https://arxiv.org/abs/1301.3781) Paper _Efficient Estimation of Word Representations in Vector Space_ by _Mikolov et al._ published in 2013 introducing Word2Vec
* [GloVe](https://nlp.stanford.edu/pubs/glove.pdf) Paper _GloVe: Global Vectors for Word Representation_ by _Pennington_ et al._ published in 2014 introducing GloVe
* [WordPiece](https://arxiv.org/abs/1609.08144): Paper _Google’s Neural Machine Translation System: Bridging the Gap between Human and Machine Translation_ by _Yonghui Wu et al._ published in 2016 introducing WordPiece (used in BERT)
* [SentencePiece](https://arxiv.org/abs/1808.06226): Paper _SentencePiece: A simple and language independent subword tokenizer and detokenizer for Neural Text Processing_ by _Taku Kudo and John Richardson_ presented in EMNLP 2018 that introduces a language-independent tokenizer
* [ELMo](https://arxiv.org/abs/1802.05365) Paper _Deep contextualized word representations_ by _Peters et al._ introducing ELMo __a context-sensitive embedding__
* [ByT5](https://arxiv.org/abs/2105.13626): Paper _ByT5: Towards a token-free future with pre-trained byte-to-byte models_ by _Xue et al._ presented in ACL 2022 proposing ByT5

#### Language Modelling
* [LMs](https://www.bishopbook.com/): Chapter 12 of [[BB]](https://www.bishopbook.com/) __Section 12.2__
* [N-Gram LMs](https://web.stanford.edu/~jurafsky/slp3/3.pdf): Chapter 3 of _Speech and Language Processing;_ __Section 3.1__ on N-gram LM
* [Maximum Likelihood](https://www.bishopbook.com/): Chapter 2 of [[BB]](https://www.bishopbook.com/) __Sections 12.1 -- 12.3__

#### Recurrent LMs
* [Recurrent LMs](https://web.stanford.edu/~jurafsky/slp3/8.pdf): Chapter 8 of [[JM]](https://web.stanford.edu/~jurafsky/slp3/)
* [LSTM LMs](https://arxiv.org/abs/1708.02182): Paper _Regularizing and Optimizing LSTM Language Models_ by _Stephen Merity, Nitish Shirish Keskar, and Richard Socher_ published in ICLR 2018 enabling LSTMs to perform strongly on word-level language modeling
* [High-Rank Recurrent LMs](https://arxiv.org/abs/1711.03953): Paper _Breaking the Softmax Bottleneck: A High-Rank RNN Language Model_ by _Zhilin Yang, Zihang Dai, Ruslan Salakhutdinov, and William W. Cohen_ presented at ICLR 2018 proposing Mixture of Softmaxes (MoS) and achieving state-of-the-art results at the time


#### Transformer-based LMs and LLMs
* [Transformer LMs](https://www.bishopbook.com/): Chapter 12 of [[BB]](https://www.bishopbook.com/) __Section 12.3__
* [LLMs via Transformers](https://web.stanford.edu/~jurafsky/slp3/10.pdf): Chapter 10 of [[JM]](https://web.stanford.edu/~jurafsky/slp3/)

#### GPTs
* [GPT-1](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf): Paper _Improving Language Understanding by Generative Pre-Training_ by _Alec Radford et al._ (OpenAI, 2018) that introduced GPT-1 and revived the idea of pretraining transformers as LMs followed by supervised fine-tuning
* [GPT-2](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf): Paper _Language Models are Unsupervised Multitask Learners_ by _Alec Radford et al._ (OpenAI, 2019) that introduces GPT-2 with 1.5B parameter trained on web text
* [GPT-3](https://arxiv.org/abs/2005.14165): Paper _Language Models are Few-Shot Learners_ by _Tom B. Brown et al._ (OpenAI, 2020) that introduces GPT-3, a 175B-parameter transformer LM 
* [GPT-4](https://arxiv.org/abs/2303.08774): _GPT-4 Technical Report_ by _OpenAI_ (2023) that provides an overview of GPT-4’s capabilities


#### Other LLMs
* [BERT](https://arxiv.org/abs/1810.04805): Paper _BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding_ by _Jacob Devlin et al._ presented at NAACL 2019 that introduced BERT
<!-- * [XLNet: Generalized Autoregressive Pretraining for Language Understanding](https://arxiv.org/abs/1906.08237): Paper _XLNet: Generalized Autoregressive Pretraining for Language Understanding_ by _Zhilin Yang et al._ presented at NeurIPS 2019 that introduces XLNet -->
* [RoBERTa](https://arxiv.org/abs/1907.11692): Paper _RoBERTa: A Robustly Optimized BERT Pretraining Approach_ by _Yinhan Liu, et al._ (Facebook AI, 2019) that shows BERT's performance can be significantly improved by more data, longer training, and removing next sentence prediction
* [T5](https://arxiv.org/abs/1910.10683): Paper _Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer_ by _Colin Raffel et al._ (JMLR 2020) that reformulates all NLP tasks as text-to-text problems introducing the T5 model

#### Data for LLMs
* [The Pile](https://arxiv.org/abs/2101.00027): Paper _The Pile: An 800GB Dataset of Diverse Text for Language Modeling_ by _Leo Gao et al._ presented in 2020 introductin dataset __The Pile__
* [RACE](https://arxiv.org/abs/1704.04683): Paper _RACE: Large-scale Reading Comprehension Dataset from Examinations_ by _Guokun Lai et al._ presented at EMNLP in 2017 introducing a large-scale dataset of English reading comprehension questions from real-world exams
* [BookCorpus](https://arxiv.org/abs/1511.06398): Paper _Aligning Books and Movies: Towards Story-like Visual Explanations by Watching Movies and Reading Books_ by _Yukun Zhu et al._ presented at ICCV in 2015 introducing the dataset BookCorpus. It was used to pre-train GPT-1 and BERT; nevertheless, it turned out that the dataset was collected without authors consent; see [the Wikipedia article](https://en.wikipedia.org/wiki/BookCorpus). It was hence replaced later with BookCorpusOpen
* [Documentation Debt](https://arxiv.org/abs/2105.05241): Paper _Addressing "Documentation Debt" in Machine Learning Research: A Retrospective Datasheet for BookCorpus_ by _Jack Bandy and Nicholas Vincent_ published in 2021 discussing the efficiency and legality of data collection by looking into [BookCorpus](https://arxiv.org/abs/1511.06398)

#### Earlier Work on Pretraining
* [SSL](https://arxiv.org/abs/1511.01432): Paper _Semi-supervised Sequence Learning_ by _Andrew M. Dai et al._ published in 2015 that explores using unsupervised pretraining followed by supervised fine-tuning; this was an early solid work advocating __pre-training__ idea for LMs
* [ULMFiT](https://arxiv.org/abs/1801.06146): Paper _Universal Language Model Fine-tuning for Text Classification_ by _Jeremy Howard et al._ presented at ACL in 2018 introducing ULMFiT that uses pre-trained LMs with task-specific fine-tuning

#### Fine-tuning
* [LMs](https://www.bishopbook.com/): Chapter 12 of [[BB]](https://www.bishopbook.com/) __Section 12.3.5__
* [LoRA](https://arxiv.org/abs/2106.09685): Paper _LoRA: Low-Rank Adaptation of Large Language Models_ by _Edward J. Hu et al._ presented at ICLR in 2022 introducing LoRA
* [ReFT](https://arxiv.org/abs/2404.03592): Paper _ReFT: Representation Finetuning for Language Models_ by _Z. Wu et al._ presented at NeurIPS in 2024 proposing an alternative fine-tuning algorithm

#### Prompt Design
* [Zero-Shot](https://arxiv.org/abs/1707.00600): Paper _Zero-shot Learning — A Comprehensive Evaluation of the Good, the Bad and the Ugly_ by _Yongqin Xian et al._ at IEEE Tran. PAMI in 2018 presenting an overview on zero-shot learning
* [Chain-of-Thought](https://arxiv.org/abs/2201.11903): Paper _Chain-of-Thought Prompting Elicits Reasoning in Large Language Models_ by _Jason Wei et al._ presented at NeurIPS in 2022 introducing __chain-of-thought__ prompting
* [Prefix-Tuning](https://arxiv.org/abs/2101.00190): Paper _Prefix-Tuning: Optimizing Continuous Prompts for Generation_ by _Xiang Lisa Li et al._ presented at ACL in 2021 proposing prefix-tuning approach for prompting
* [Prompt-Tuning](https://arxiv.org/abs/2104.08691): Paper _The Power of Scale for Parameter-Efficient Prompt Tuning_ by _B. Lester et al._ presented at EMNLP in 2021 proposing the prompt tuning idea, i.e., learning to prompt
* [Zero-Shot LLMs](https://arxiv.org/abs/2205.11916): Paper _Large Language Models are Zero-Shot Reasoners_ by _T. Kojima et al._ presented at NeurIPS in 2022 studying zero-shot learning with LLMs
* [Prompt Engineering is Dead](https://spectrum.ieee.org/prompt-engineering-is-dead): Article _AI Prompt Engineering Is Dead: Long Live AI Prompt Engineering_ by _Dina Genkina_ published in _IEEE Spectrum_ in 2024

#### Foundation Models
* [CRFM](https://crfm.stanford.edu/) Center for Research on Foundation Models who coined the term _Foundation Model_

### Chapter 2: Data Generation Problem
#### Basic Definitions
* [Probabilistic Model](https://www.bishopbook.com/): Chapter 2 of [[BB]](https://www.bishopbook.com/) __Sections 2.4 to 2.6__
* [Statistics](https://probml.github.io/pml-book/book2.html): Chapter 3 of [[M]](https://probml.github.io/pml-book/book2.html) __Sections 3.1 to 3.3__
* [Bayesian Statistics](https://www.deeplearningbook.org/): Chapter 5 of [[GYC]](https://www.deeplearningbook.org/) __Section 5.6__

#### Generative and Discriminative Learning
* [Discriminative and Generative Models](https://www.bishopbook.com/): Chapter 5 of [[BB]](https://www.bishopbook.com/)


#### Generative Models
* [Naive Bayes](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1751-5823.2001.tb00465.x?casa_token=DH9SI9elEXQAAAAA%3AVgLUtFs8TJVMldMvLbOhXTuvkyubn3CDcSaE7xD9fe02YwcTwBik5fEpAY1SpcMvl0kJZuwHqrKbIA): Paper _Idiot's Bayes—Not So Stupid After All?_ by _D. Hand and K. Yu_ published at _Statistical Review_ in 2001 discussing the efficiency of Naive Bayes for classification
* [Naive Bayes vs Linear Regression](https://proceedings.neurips.cc/paper/2001/hash/7b7a53e239400a13bd6be6c91c4f6c4e-Abstract.html): Paper _On Discriminative vs. Generative Classifiers: A Comparison of Logistic Regression and Naive Bayes_ by _A. Ng and M. Jordan_ presented at _NeurIPS_ in 2001 elaborating the data-efficiency efficiency of Naive Bayes and asymptotic superiority of Logistic Regression
* [Generative Models -- Overview](https://probml.github.io/pml-book/book2.html): Chapter 20 of [[M]](https://probml.github.io/pml-book/book2.html) __Sections 20.1 to 20.3__

### Chapter 3: Explicit Distribution Learning

#### Sampling
* [Sampling Overview](https://www.bishopbook.com/): Chapter 14 of [[BB]](https://www.bishopbook.com/)
* [Sampling](https://www.microsoft.com/en-us/research/wp-content/uploads/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf) The book _Pattern Recognition and Machine Learning_ by Christopher Bishop. Read __Chapter 11__ to know about how challenging _sampling from a distribution_ is
* [Sampling Methods](https://www.deeplearningbook.org/): Chapter 17 of [[GYC]](https://www.deeplearningbook.org/) __Sections 17.1 and 17.2__

#### Distribution Learning via MLE
* [KL Divergence and MLE](https://probml.github.io/pml-book/book2.html): Chapter 5 of [[M]](https://probml.github.io/pml-book/book2.html) __Sections 5.1 to 5.2__
* [MLE](https://www.deeplearningbook.org/): Chapter 5 of [[GYC]](https://www.deeplearningbook.org/) __Section 5.5__
* [Maximum Likelihood Learning](http://www.inference.org.uk/itprnn/book.pdf) The book _Information Theory, Inference, and Learning Algorithms_ by David MacKay which discusses MLE for clustering in __Chapter 22__ 
* [Evaluating Distribution Learning](https://probml.github.io/pml-book/book2.html): Chapter 20 of [[M]](https://probml.github.io/pml-book/book2.html) __Sections 20.4__

#### Autoregressive Models
* [Autoregressive Models](https://probml.github.io/pml-book/book2.html): Chapter 22 of [[M]](https://probml.github.io/pml-book/book2.html)
* [PixelRNN and PixelCNN](https://arxiv.org/abs/1601.06759): Paper _Pixel Recurrent Neural Networks_ by _A. Oord et al._ presented at _ICMLR_ in 2016 proposing PixelRNN and PixelCNN
* [ImageGPT](https://proceedings.mlr.press/v119/chen20s/chen20s.pdf): Paper _Generative Pretraining from Pixels_ by _M. Chen et al._ presented at _ICML_ in 2020 proposing ImageGPT

#### Energy-based Models