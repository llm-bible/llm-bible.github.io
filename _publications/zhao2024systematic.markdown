---
layout: publication
title: 'Snfinllm: Systematic And Nuanced Financial Domain Adaptation Of Chinese Large Language Models'
authors: Shujuan Zhao, Lingfeng Qiao, Kangyang Luo, Qian-wen Zhang, Junru Lu, Di Yin
conference: "Arxiv"
year: 2024
bibkey: zhao2024systematic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.02302'}
  - {name: "Code", url: 'https://www.youtube.com/watch?v=GYT-65HZwus'}
tags: ['Has Code', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Large language models (LLMs) have become powerful tools for advancing natural
language processing applications in the financial industry. However, existing
financial LLMs often face challenges such as hallucinations or superficial
parameter training, resulting in suboptimal performance, particularly in
financial computing and machine reading comprehension (MRC). To address these
issues, we propose a novel large language model specifically designed for the
Chinese financial domain, named SNFinLLM. SNFinLLM excels in domain-specific
tasks such as answering questions, summarizing financial research reports,
analyzing sentiment, and executing financial calculations. We then perform the
supervised fine-tuning (SFT) to enhance the model's proficiency across various
financial domains. Specifically, we gather extensive financial data and create
a high-quality instruction dataset composed of news articles, professional
papers, and research reports of finance domain. Utilizing both domain-specific
and general datasets, we proceed with continuous pre-training on an established
open-source base model, resulting in SNFinLLM-base. Following this, we engage
in supervised fine-tuning (SFT) to bolster the model's capability across
multiple financial tasks. Crucially, we employ a straightforward Direct
Preference Optimization (DPO) method to better align the model with human
preferences. Extensive experiments conducted on finance benchmarks and our
evaluation dataset demonstrate that SNFinLLM markedly outperforms other
state-of-the-art financial language models. For more details, check out our
demo video here: https://www.youtube.com/watch?v=GYT-65HZwus.
