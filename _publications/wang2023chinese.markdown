---
layout: publication
title: 'Aurora:activating Chinese Chat Capability For Mixtral-8x7b Sparse Mixture-of-experts Through Instruction-tuning'
authors: Rongsheng Wang, Haoming Chen, Ruizhe Zhou, Yaofei Duan, Kunyan Cai, Han Ma, Jiaxi Cui, Jian Li, Patrick Cheong-iao Pang, Yapeng Wang, Tao Tan
conference: "Arxiv"
year: 2023
bibkey: wang2023chinese
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.14557'}
  - {name: "Code", url: 'https://github.com/WangRongsheng/Aurora'}
tags: ['Has Code', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
Existing research has demonstrated that refining large language models (LLMs)
through the utilization of machine-generated instruction-following data
empowers these models to exhibit impressive zero-shot capabilities for novel
tasks, without requiring human-authored instructions. In this paper, we
systematically investigate, preprocess, and integrate three Chinese
instruction-following datasets with the aim of enhancing the Chinese
conversational capabilities of Mixtral-8x7B sparse Mixture-of-Experts model.
Through instruction fine-tuning on this carefully processed dataset, we
successfully construct the Mixtral-8x7B sparse Mixture-of-Experts model named
"Aurora." To assess the performance of Aurora, we utilize three widely
recognized benchmark tests: C-Eval, MMLU, and CMMLU. Empirical studies validate
the effectiveness of instruction fine-tuning applied to Mixtral-8x7B sparse
Mixture-of-Experts model. This work is pioneering in the execution of
instruction fine-tuning on a sparse expert-mixed model, marking a significant
breakthrough in enhancing the capabilities of this model architecture. Our
code, data and model are publicly available at
  https://github.com/WangRongsheng/Aurora
