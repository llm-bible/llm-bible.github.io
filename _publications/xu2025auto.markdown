---
layout: publication
title: 'Auto-search And Refinement: An Automated Framework For Gender Bias Mitigation In Large Language Models'
authors: Yue Xu, Chengyan Fu, Li Xiong, Sibei Yang, Wenjie Wang
conference: "Arxiv"
year: 2025
bibkey: xu2025auto
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.11559"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'Bias Mitigation', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training']
---
Pre-training large language models (LLMs) on vast text corpora enhances
natural language processing capabilities but risks encoding social biases,
particularly gender bias. While parameter-modification methods like fine-tuning
mitigate bias, they are resource-intensive, unsuitable for closed-source
models, and lack adaptability to evolving societal norms. Instruction-based
approaches offer flexibility but often compromise task performance. To address
these limitations, we propose \\(\textit\{FaIRMaker\}\\), an automated and
model-independent framework that employs an \\(\textbf\{auto-search and
refinement\}\\) paradigm to adaptively generate Fairwords, which act as
instructions integrated into input queries to reduce gender bias and enhance
response quality. Extensive experiments demonstrate that \\(\textit\{FaIRMaker\}\\)
automatically searches for and dynamically refines Fairwords, effectively
mitigating gender bias while preserving task integrity and ensuring
compatibility with both API-based and open-source LLMs.
