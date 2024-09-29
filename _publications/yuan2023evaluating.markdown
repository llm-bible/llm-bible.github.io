---
layout: publication
title: Evaluating Instruction-Tuned Large Language Models on Code Comprehension and Generation
authors: Yuan Zhiqiang, Liu Junwei, Zi Qiancheng, Liu Mingwei, Peng Xin, Lou Yiling
conference: "Arxiv"
year: 2023
bibkey: yuan2023evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.01240"}
tags: ['Few Shot', 'Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
In this work we evaluate 10 open-source instructed LLMs on four representative code comprehension and generation tasks. We have the following main findings. First for the zero-shot setting instructed LLMs are very competitive on code comprehension and generation tasks and sometimes even better than small SOTA models specifically fine-tuned on each downstream task. We also find that larger instructed LLMs are not always better on code-related tasks. Second for the few-shot setting we find that adding demonstration examples substantially helps instructed LLMs perform better on most code comprehension and generation tasks; however the examples would sometimes induce unstable or even worse performance. Furthermore we find widely-used BM25-based shot selection strategy significantly outperforms the basic random selection or fixed selection only on generation problems. Third for the fine-tuning setting we find that fine-tuning could further improve the model performance on downstream code comprehension and generation tasks compared to the zero-shot/one-shot performance. In addition after being fine-tuned on the same downstream task dataset instructed LLMs outperform both the small SOTA models and similar-scaled LLMs without instruction tuning. Based on our findings we further present practical implications on model and usage recommendation performance and cost trade-offs and future direction.
