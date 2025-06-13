---
layout: publication
title: 'Fine-tuning A Large Language Model For Automating Computational Fluid Dynamics Simulations'
authors: Zhehao Dong, Zhen Lu, Yue Yang
conference: "Arxiv"
year: 2025
bibkey: dong2025fine
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.09602'}
  - {name: "Code", url: 'https://github.com/YYgroup/AutoCFD'}
tags: ['Agentic', 'Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Configuring computational fluid dynamics (CFD) simulations typically demands
extensive domain expertise, limiting broader access. Although large language
models (LLMs) have advanced scientific computing, their use in automating CFD
workflows is underdeveloped. We introduce a novel approach centered on
domain-specific LLM adaptation. By fine-tuning Qwen2.5-7B-Instruct on NL2FOAM,
our custom dataset of 28716 natural language-to-OpenFOAM configuration pairs
with chain-of-thought (CoT) annotations, we enable direct translation from
natural language descriptions to executable CFD setups. A multi-agent framework
orchestrates the process, autonomously verifying inputs, generating
configurations, running simulations, and correcting errors. Evaluation on a
benchmark of 21 diverse flow cases demonstrates state-of-the-art performance,
achieving 88.7% solution accuracy and 82.6% first-attempt success rate. This
significantly outperforms larger general-purpose models like
Qwen2.5-72B-Instruct, DeepSeek-R1, and Llama3.3-70B-Instruct, while also
requiring fewer correction iterations and maintaining high computational
efficiency. The results highlight the critical role of domain-specific
adaptation in deploying LLM assistants for complex engineering workflows. Our
code and fine-tuned model have been deposited at
https://github.com/YYgroup/AutoCFD.
