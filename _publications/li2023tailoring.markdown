---
layout: publication
title: 'Tailoring Personality Traits In Large Language Models Via Unsupervisedly-built Personalized Lexicons'
authors: Tianlong Li, Shihan Dou, Changze Lv, Wenhao Liu, Jianhan Xu, Muling Wu, Zixuan Ling, Xiaoqing Zheng, Xuanjing Huang
conference: "Arxiv"
year: 2023
bibkey: li2023tailoring
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.16582'}
tags: ['Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Pretraining Methods']
---
Personality plays a pivotal role in shaping human expression patterns, thus
regulating the personality of large language models (LLMs) holds significant
potential in enhancing the user experience of LLMs. Previous methods either
relied on fine-tuning LLMs on specific corpora or necessitated manually crafted
prompts to elicit specific personalities from LLMs. However, the former
approach is inefficient and costly, while the latter cannot precisely
manipulate personality traits at a fine-grained level. To address the above
challenges, we have employed a novel Unsupervisedly-Built Personalized Lexicons
(UBPL) in a pluggable manner during the decoding phase of LLMs to manipulate
their personality traits. UBPL is a lexicon built through an unsupervised
approach from a situational judgment test dataset (SJTs4LLM). Users can utilize
UBPL to adjust the probability vectors of predicted words in the decoding phase
of LLMs, thus influencing the personality expression of LLMs. Extensive
experimentation demonstrates the remarkable effectiveness and pluggability of
our method for fine-grained manipulation of LLM's personality.
