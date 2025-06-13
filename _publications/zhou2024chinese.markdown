---
layout: publication
title: 'Lawgpt: A Chinese Legal Knowledge-enhanced Large Language Model'
authors: Zhi Zhou, Jiang-xin Shi, Peng-xiao Song, Xiao-wen Yang, Yi-xuan Jin, Lan-zhe Guo, Yu-feng Li
conference: "Arxiv"
year: 2024
bibkey: zhou2024chinese
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04614"}
  - {name: "Code", url: "https://github.com/pengxiao-song/LaWGPT"}
tags: ['Training Techniques', 'Model Architecture', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Pre-Training', 'Applications']
---
Large language models (LLMs), including both proprietary and open-source
models, have showcased remarkable capabilities in addressing a wide range of
downstream tasks. Nonetheless, when it comes to practical Chinese legal tasks,
these models fail to meet the actual requirements. Proprietary models do not
ensure data privacy for sensitive legal cases, while open-source models
demonstrate unsatisfactory performance due to their lack of legal knowledge. To
address this problem, we introduce LawGPT, the first open-source model
specifically designed for Chinese legal applications. LawGPT comprises two key
components: legal-oriented pre-training and legal supervised fine-tuning.
Specifically, we employ large-scale Chinese legal documents for legal-oriented
pre-training to incorporate legal domain knowledge. To further improve the
model's performance on downstream legal tasks, we create a knowledge-driven
instruction dataset for legal supervised fine-tuning. Our experimental results
demonstrate that LawGPT outperforms the open-source LLaMA 7B model. Our code
and resources are publicly available at https://github.com/pengxiao-song/LaWGPT
and have received 5.7K stars on GitHub.
