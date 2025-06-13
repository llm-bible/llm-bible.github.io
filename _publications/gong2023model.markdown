---
layout: publication
title: 'Model-generated Pretraining Signals Improves Zero-shot Generalization Of Text-to-text Transformers'
authors: Linyuan Gong, Chenyan Xiong, Xiaodong Liu, Payal Bajaj, Yiqing Xie, Alvin Cheung, Jianfeng Gao, Xia Song
conference: "Arxiv"
year: 2023
bibkey: gong2023model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12567"}
  - {name: "Code", url: "https://github.com/gonglinyuan/metro_t0"}
tags: ['Transformer', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting']
---
This paper explores the effectiveness of model-generated signals in improving
zero-shot generalization of text-to-text Transformers such as T5. We study
various designs to pretrain T5 using an auxiliary model to construct more
challenging token replacements for the main model to denoise. Key aspects under
study include the decoding target, the location of the RTD head, and the
masking pattern. Based on these studies, we develop a new model, METRO-T0,
which is pretrained using the redesigned ELECTRA-Style pretraining strategies
and then prompt-finetuned on a mixture of NLP tasks. METRO-T0 outperforms all
similar-sized baselines on prompted NLP benchmarks, such as T0 Eval and MMLU,
and rivals the state-of-the-art T0-11B model with only 8% of its parameters.
Our analysis on model's neural activation and parameter sensitivity reveals
that the effectiveness of METRO-T0 stems from more balanced contribution of
parameters and better utilization of their capacity. The code and model
checkpoints are available at https://github.com/gonglinyuan/metro_t0.
