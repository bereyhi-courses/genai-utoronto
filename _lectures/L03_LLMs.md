---
type: lecture
date: 2026-05-12T18:00:00-4:00
title: "Lecture 6: Large Language Models"
tldr: "LLMs"
stat: lec
# for lectures stat: lec
description: We study LLMs which are Large LMs trained on large corpora. We see how they can be evaluated, fine-tuned, and/or deployed via prompt design. 
videoID: 3931lLpmXuM 
hide_from_announcments: false
---
**Lecture Notes:**
- [Chapter 1 - Section 3]({{ site.baseurl }}/assets/Notes/CH1/CH1_Sec3.pdf)

**Further Reads:**

**GPT Papers:**
* [GPT-1](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf): Paper _Improving Language Understanding by Generative Pre-Training_ by _Alec Radford et al._ (OpenAI, 2018) that introduced GPT-1 and revived the idea of pretraining transformers as LMs followed by supervised fine-tuning
* [GPT-2](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf): Paper _Language Models are Unsupervised Multitask Learners_ by _Alec Radford et al._ (OpenAI, 2019) that introduces GPT-2 with 1.5B parameter trained on web text
* [GPT-3](https://arxiv.org/abs/2005.14165): Paper _Language Models are Few-Shot Learners_ by _Tom B. Brown et al._ (OpenAI, 2020) that introduces GPT-3, a 175B-parameter transformer LM 
* [GPT-4](https://arxiv.org/abs/2303.08774): _GPT-4 Technical Report_ by _OpenAI_ (2023) that provides an overview of GPT-4’s capabilities

**Data for LLMs:**
* [The Pile](https://arxiv.org/abs/2101.00027): Paper _The Pile: An 800GB Dataset of Diverse Text for Language Modeling_ by _Leo Gao et al._ presented in 2020 introductin dataset __The Pile__
* [Documentation Debt](https://arxiv.org/abs/2105.05241): Paper _Addressing "Documentation Debt" in Machine Learning Research: A Retrospective Datasheet for BookCorpus_ by _Jack Bandy and Nicholas Vincent_ published in 2021 discussing the efficiency and legality of data collection by looking into [BookCorpus](https://arxiv.org/abs/1511.06398)

**Fine-tuning:**
* [SSL](https://arxiv.org/abs/1511.01432): Paper _Semi-supervised Sequence Learning_ by _Andrew M. Dai et al._ published in 2015 that explores using unsupervised pretraining followed by supervised fine-tuning; this was an early solid work advocating __pre-training__ idea for LMs
* [LoRA](https://arxiv.org/abs/2106.09685): Paper _LoRA: Low-Rank Adaptation of Large Language Models_ by _Edward J. Hu et al._ presented at ICLR in 2022 introducing LoRA

**Prompt Design:**
* [Prefix-Tuning](https://arxiv.org/abs/2101.00190): Paper _Prefix-Tuning: Optimizing Continuous Prompts for Generation_ by _Xiang Lisa Li et al._ presented at ACL in 2021 proposing prefix-tuning approach for prompting
* [Prompt-Tuning](https://arxiv.org/abs/2104.08691): Paper _The Power of Scale for Parameter-Efficient Prompt Tuning_ by _B. Lester et al._ presented at EMNLP in 2021 proposing the prompt tuning idea, i.e., learning to prompt
* [Zero-Shot LLMs](https://arxiv.org/abs/2205.11916): Paper _Large Language Models are Zero-Shot Reasoners_ by _T. Kojima et al._ presented at NeurIPS in 2022 studying zero-shot learning with LLMs
