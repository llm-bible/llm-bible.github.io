---
layout: publication
title: 'Ba-lora: Bias-alleviating Low-rank Adaptation To Mitigate Catastrophic Inheritance In Large Language Models'
authors: Yupeng Chang, Yi Chang, Yuan Wu
conference: "Arxiv"
year: 2024
bibkey: chang2024ba
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.04556"}
  - {name: "Code", url: "https://github.com/cyp-jlu-ai/BA-LoRA"}
tags: ['Training Techniques', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Pre-Training', 'Applications']
---
Large language models (LLMs) have demonstrated remarkable proficiency across various natural language processing (NLP) tasks. However, adapting LLMs to downstream applications requires computationally intensive and memory-demanding fine-tuning procedures. To alleviate these burdens, parameter-efficient fine-tuning (PEFT) techniques have emerged as a promising approach to tailor LLMs with minimal computational overhead. While PEFT methods offer substantial advantages, they do not fully address the pervasive issue of bias propagation from pre-training data. This work introduces Bias-Alleviating Low-Rank Adaptation (BA-LoRA), a novel PEFT method designed to counteract bias inheritance. BA-LoRA incorporates three distinct regularization terms: (1) a consistency regularizer, (2) a diversity regularizer, and (3) a singular value decomposition regularizer. These regularizers aim to enhance the models' consistency, diversity, and generalization capabilities during fine-tuning. We conduct extensive experiments on natural language understanding (NLU) and natural language generation (NLG) tasks using prominent LLMs such as LLaMA, Mistral, and Gemma. The results demonstrate that BA-LoRA outperforms LoRA and its state-of-the-art variants. Moreover, the extended experiments demonstrate that our method effectively mitigates the adverse effects of pre-training bias, leading to more reliable and robust model outputs. The code is available at https://github.com/cyp-jlu-ai/BA-LoRA.
