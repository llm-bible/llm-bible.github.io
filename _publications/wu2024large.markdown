---
layout: publication
title: Large Language Models Can Self45;correct With Minimal Effort
authors: Wu Zhenyu, Zeng Qingkai, Zhang Zhihan, Tan Zhaoxuan, Shen Chao, Jiang Meng
conference: "Arxiv"
year: 2024
bibkey: wu2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.14092"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Tools']
---
Intrinsic self45;correct was a method that instructed large language models (LLMs) to verify and correct their responses without external feedback. Unfortunately the study concluded that the LLMs could not self45;correct reasoning yet. We find that a simple yet effective verification method can unleash inherent capabilities of the LLMs. That is to mask a key condition in the question add the current response to construct a verification question and predict the condition to verify the response. The condition can be an entity in an open45;domain question or a numeric value in a math question which requires minimal effort (via prompting) to identify. We propose an iterative verify45;then45;correct framework to progressively identify and correct (probably) false responses named ProCo. We conduct experiments on three reasoning tasks. On average ProCo with GPT45;3.545;Turbo as the backend LLM yields +6.8 exact match on four open45;domain question answering datasets +14.1 accuracy on three arithmetic reasoning datasets and +9.6 accuracy on a commonsense reasoning dataset compared to Self45;Correct.
