---
layout: publication
title: Fine45;grained Detoxification Via Instance45;level Prefixes For Large Language Models
authors: Yi Xin, Wang Linlin, Wang Xiaoling, He Liang
conference: "Arxiv"
year: 2024
bibkey: yi2024fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15202"}
tags: ['Applications', 'Attention Mechanism', 'Language Modeling', 'Model Architecture', 'Prompting', 'Training Techniques']
---
Impressive results have been achieved in natural language processing (NLP) tasks through the training of large language models (LLMs). However these models occasionally produce toxic content such as insults threats and profanity in response to certain prompts thereby constraining their practical utility. To tackle this issue various finetuning45;based and decoding45;based approaches have been utilized to mitigate toxicity. However these methods typically necessitate additional costs such as high45;quality training data or auxiliary models. In this paper we propose fine45;grained detoxification via instance45;level prefixes (FGDILP) to mitigate toxic text without additional cost. Specifically FGDILP contrasts the contextualized representation in attention space using a positive prefix45;prepended prompt against multiple negative prefix45;prepended prompts at the instance level. This allows for constructing fine45;grained subtoxicity vectors which enables collaborative detoxification by fusing them to correct the normal generation process when provided with a raw prompt. We validate that FGDILP enables controlled text generation with regard to toxicity at both the utterance and context levels. Our method surpasses prompt45;based baselines in detoxification although at a slight cost to generation fluency and diversity.
