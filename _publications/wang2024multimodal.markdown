---
layout: publication
title: 'M\(^2\)PT: Multimodal Prompt Tuning For Zero-shot Instruction Learning'
authors: Taowen Wang, Yiyang Liu, James Chenhao Liang, Junhan Zhao, Yiming Cui, Yuning Mao, Shaoliang Nie, Jiahao Liu, Fuli Feng, Zenglin Xu, Cheng Han, Lifu Huang, Qifan Wang, Dongfang Liu
conference: "Arxiv"
year: 2024
bibkey: wang2024multimodal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.15657'}
tags: ['Reinforcement Learning', 'Prompting', 'Efficiency and Optimization', 'Multimodal Models']
---
Multimodal Large Language Models (MLLMs) demonstrate remarkable performance
across a wide range of domains, with increasing emphasis on enhancing their
zero-shot generalization capabilities for unseen tasks across various
modalities. Instruction tuning has emerged as an effective strategy for
achieving zero-shot generalization by finetuning pretrained models on diverse
multimodal tasks. As the scale of MLLMs continues to grow, parameter-efficient
finetuning becomes increasingly critical. However, most existing
parameter-efficient approaches focus only on single modalities and often
overlook the multimodal characteristics during finetuning. In this work, we
introduce a novel Multimodal Prompt Tuning (M\\(^2\\)PT) approach for efficient
instruction tuning of MLLMs. M\\(^2\\)PT effectively integrates visual and textual
prompts into the vision encoder and language processor respectively during
finetuning, facilitating the extraction and alignment of features across
modalities. Empirical results on various multimodal evaluation datasets
demonstrate the superior performance of our approach compared to several
state-of-the-art baselines. A comprehensive set of ablation studies validates
the effectiveness of our prompt design and the efficiency of our approach.
