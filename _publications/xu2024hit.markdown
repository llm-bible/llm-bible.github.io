---
layout: publication
title: 'Hit The Sweet Spot! Span-level Ensemble For Large Language Models'
authors: Yangyifan Xu, Jianghao Chen, Junhong Wu, Jiajun Zhang
conference: "Arxiv"
year: 2024
bibkey: xu2024hit
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.18583'}
tags: ['RAG', 'Security', 'Merging']
---
Ensembling various LLMs to unlock their complementary potential and leverage
their individual strengths is highly valuable. Previous studies typically focus
on two main paradigms: sample-level and token-level ensembles. Sample-level
ensemble methods either select or blend fully generated outputs, which hinders
dynamic correction and enhancement of outputs during the generation process. On
the other hand, token-level ensemble methods enable real-time correction
through fine-grained ensemble at each generation step. However, the information
carried by an individual token is quite limited, leading to suboptimal
decisions at each step. To address these issues, we propose SweetSpan, a
span-level ensemble method that effectively balances the need for real-time
adjustments and the information required for accurate ensemble decisions. Our
approach involves two key steps: First, we have each candidate model
independently generate candidate spans based on the shared prefix. Second, we
calculate perplexity scores to facilitate mutual evaluation among the candidate
models and achieve robust span selection by filtering out unfaithful scores. To
comprehensively evaluate ensemble methods, we propose a new challenging setting
(ensemble models with significant performance gaps) in addition to the standard
setting (ensemble the best-performing models) to assess the performance of
model ensembles in more realistic scenarios. Experimental results in both
standard and challenging settings across various language generation tasks
demonstrate the effectiveness, robustness, and versatility of our approach
compared with previous ensemble methods.
