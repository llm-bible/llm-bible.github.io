---
layout: publication
title: Improving Factual Consistency of Text Summarization by Adversarially Decoupling Comprehension and Embellishment Abilities of LLMs
authors: Feng Huawen, Fan Yan, Liu Xiong, Lin Ting-en, Yao Zekun, Wu Yuchuan, Huang Fei, Li Yongbin, Ma Qianli
conference: "Arxiv"
year: 2023
bibkey: feng2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.19347"}
tags: ['Applications', 'Arxiv']
---
Despite the recent progress in text summarization made by large language models (LLMs) they often generate summaries that are factually inconsistent with original articles known as hallucinations in text generation. Unlike previous small models (e.g. BART T5) current LLMs make fewer silly mistakes but more sophisticated ones such as imposing cause and effect adding false details overgeneralizing etc. These hallucinations are challenging to detect through traditional methods which poses great challenges for improving the factual consistency of text summarization. In this paper we propose an adversarially DEcoupling method to disentangle the Comprehension and EmbellishmeNT abilities of LLMs (DECENT). Furthermore we adopt a probing-based efficient training to cover the shortage of sensitivity for true and false in the training process of LLMs. In this way LLMs are less confused about embellishing and understanding; thus they can execute the instructions more accurately and have enhanced abilities to distinguish hallucinations. Experimental results show that DECENT significantly improves the reliability of text summarization based on LLMs.
