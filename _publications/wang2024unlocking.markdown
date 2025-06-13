---
layout: publication
title: 'Unlocking Memorization In Large Language Models With Dynamic Soft Prompting'
authors: Zhepeng Wang, Runxue Bao, Yawen Wu, Jackson Taylor, Cao Xiao, Feng Zheng, Weiwen Jiang, Shangqian Gao, Yanfu Zhang
conference: "Arxiv"
year: 2024
bibkey: wang2024unlocking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13853"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Language Modeling', 'Pretraining Methods', 'Transformer', 'Prompting', 'Applications']
---
Pretrained large language models (LLMs) have revolutionized natural language
processing (NLP) tasks such as summarization, question answering, and
translation. However, LLMs pose significant security risks due to their
tendency to memorize training data, leading to potential privacy breaches and
copyright infringement. Accurate measurement of this memorization is essential
to evaluate and mitigate these potential risks. However, previous attempts to
characterize memorization are constrained by either using prefixes only or by
prepending a constant soft prompt to the prefixes, which cannot react to
changes in input. To address this challenge, we propose a novel method for
estimating LLM memorization using dynamic, prefix-dependent soft prompts. Our
approach involves training a transformer-based generator to produce soft
prompts that adapt to changes in input, thereby enabling more accurate
extraction of memorized data. Our method not only addresses the limitations of
previous methods but also demonstrates superior performance in diverse
experimental settings compared to state-of-the-art techniques. In particular,
our method can achieve the maximum relative improvement of 112.75% and 32.26%
over the vanilla baseline in terms of discoverable memorization rate for the
text generation task and code generation task respectively.
