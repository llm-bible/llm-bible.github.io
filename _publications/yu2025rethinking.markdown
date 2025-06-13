---
layout: publication
title: 'Rethinking The Generation Of High-quality Cot Data From The Perspective Of Llm-adaptive Question Difficulty Grading'
authors: Qianjin Yu, Keyu Wu, Zihan Chen, Chushu Zhang, Manlin Mei, Lingjun Huang, Fang Tan, Yongsheng Du, Kunlin Liu, Yurui Zhu
conference: "Arxiv"
year: 2025
bibkey: yu2025rethinking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.11919'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Recently, DeepSeek-R1 (671B) (DeepSeek-AIet al., 2025) has demonstrated its
excellent reasoning ability in complex tasks and has publiclyshared its
methodology. This provides potentially high-quality chain-of-thought (CoT) data
for stimulating the reasoning abilities of small-sized large language models
(LLMs). To generate high-quality CoT data for different LLMs, we seek an
efficient method for generating high-quality CoT data with LLM-Adaptive
questiondifficulty levels. First, we grade the difficulty of the questions
according to the reasoning ability of the LLMs themselves and construct a
LLM-Adaptive question database. Second, we sample the problem database based on
a distribution of difficulty levels of the questions and then use DeepSeek-R1
(671B) (DeepSeek-AI et al., 2025) to generate the corresponding high-quality
CoT data with correct answers. Thanks to the construction of CoT data with
LLM-Adaptive difficulty levels, we have significantly reduced the cost of data
generation and enhanced the efficiency of model supervised fine-tuning (SFT).
Finally, we have validated the effectiveness and generalizability of the
proposed method in the fields of complex mathematical competitions and code
generation tasks. Notably, with only 2k high-quality mathematical CoT data, our
ZMath-32B surpasses DeepSeek-Distill-32B in math reasoning task. Similarly,
with only 2k high-quality code CoT data, our ZCode-32B surpasses
DeepSeek-Distill-32B in code reasoning tasks.
