---
layout: publication
title: 'Fine-grained Detoxification Via Instance-level Prefixes For Large Language Models'
authors: Xin Yi, Linlin Wang, Xiaoling Wang, Liang He
conference: "Arxiv"
year: 2024
bibkey: yi2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15202"}
tags: ['Training Techniques', 'Attention Mechanism', 'Prompting', 'Model Architecture']
---
Impressive results have been achieved in natural language processing (NLP)
tasks through the training of large language models (LLMs). However, these
models occasionally produce toxic content such as insults, threats, and
profanity in response to certain prompts, thereby constraining their practical
utility. To tackle this issue, various finetuning-based and decoding-based
approaches have been utilized to mitigate toxicity. However, these methods
typically necessitate additional costs such as high-quality training data or
auxiliary models. In this paper, we propose fine-grained detoxification via
instance-level prefixes (FGDILP) to mitigate toxic text without additional
cost. Specifically, FGDILP contrasts the contextualized representation in
attention space using a positive prefix-prepended prompt against multiple
negative prefix-prepended prompts at the instance level. This allows for
constructing fine-grained subtoxicity vectors, which enables collaborative
detoxification by fusing them to correct the normal generation process when
provided with a raw prompt. We validate that FGDILP enables controlled text
generation with regard to toxicity at both the utterance and context levels.
Our method surpasses prompt-based baselines in detoxification, although at a
slight cost to generation fluency and diversity.
