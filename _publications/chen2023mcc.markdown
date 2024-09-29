---
layout: publication
title: MCC45;KD Multi45;cot Consistent Knowledge Distillation
authors: Chen Hongzhan, Wu Siyue, Quan Xiaojun, Wang Rui, Yan Ming, Zhang Ji
conference: "Arxiv"
year: 2023
bibkey: chen2023mcc
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.14747"}
tags: ['Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Prompting']
---
Large language models (LLMs) have showcased remarkable capabilities in complex reasoning through chain of thought (CoT) prompting. Recently there has been a growing interest in transferring these reasoning abilities from LLMs to smaller models. However achieving both the diversity and consistency in rationales presents a challenge. In this paper we focus on enhancing these two aspects and propose Multi45;CoT Consistent Knowledge Distillation (MCC45;KD) to efficiently distill the reasoning capabilities. In MCC45;KD we generate multiple rationales for each question and enforce consistency among the corresponding predictions by minimizing the bidirectional KL45;divergence between the answer distributions. We investigate the effectiveness of MCC45;KD with different model architectures (LLaMA/FlanT5) and various model scales (3B/7B/11B/13B) on both mathematical reasoning and commonsense reasoning benchmarks. The empirical results not only confirm MCC45;KDs superior performance on in45;distribution datasets but also highlight its robust generalization ability on out45;of45;distribution datasets.
