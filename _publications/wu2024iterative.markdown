---
layout: publication
title: 'ITERTL: An Iterative Framework For Fine-tuning Llms For RTL Code Generation'
authors: Peiyang Wu, Nan Guo, Xiao Xiao, Wenming Li, Xiaochun Ye, Dongrui Fan
conference: "Arxiv"
year: 2024
bibkey: wu2024iterative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.12022"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Recently, large language models (LLMs) have demonstrated excellent
performance, inspiring researchers to explore their use in automating register
transfer level (RTL) code generation and improving hardware design efficiency.
However, the existing approaches to fine-tune LLMs for RTL generation typically
are conducted on fixed datasets, which do not fully stimulate the capability of
LLMs and require large amounts of reference data, which are costly to acquire.
To mitigate these issues, we innovatively introduce an iterative training
paradigm named ITERTL. During each iteration, samples are drawn from the model
trained in the previous cycle. Then these new samples are employed for training
in current loop. Furthermore, we introduce a plug-and-play data filtering
strategy, thereby encouraging the model to generate high-quality,
self-contained code. Our model outperforms GPT4 and state-of-the-art (SOTA)
open-source models, achieving remarkable 53.8% pass@1 rate on VerilogEval-human
benchmark. Under similar conditions of data quantity and quality, our approach
significantly outperforms the baseline. Extensive experiments validate the
effectiveness of the proposed method.
