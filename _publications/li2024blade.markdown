---
layout: publication
title: BLADE Enhancing Black-box Large Language Models with Small Domain-Specific Models
authors: Li Haitao, Ai Qingyao, Chen Jia, Dong Qian, Wu Zhijing, Liu Yiqun, Chen Chong, Tian Qi
conference: "Arxiv"
year: 2024
bibkey: li2024blade
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.18365"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) like ChatGPT and GPT-4 are versatile and capable of addressing a diverse range of tasks. However general LLMs which are developed on open-domain data may lack the domain-specific knowledge essential for tasks in vertical domains such as legal medical etc. To address this issue previous approaches either conduct continuous pre-training with domain-specific data or employ retrieval augmentation to support general LLMs. Unfortunately these strategies are either cost-intensive or unreliable in practical applications. To this end we present a novel framework named BLADE which enhances Black-box LArge language models with small Domain-spEcific models. BLADE consists of a black-box LLM and a small domain-specific LM. The small LM preserves domain-specific knowledge and offers specialized insights while the general LLM contributes robust language comprehension and reasoning capabilities. Specifically our method involves three steps 1) pre-training the small LM with domain-specific data 2) fine-tuning this model using knowledge instruction data and 3) joint Bayesian optimization of the general LLM and the small LM. Extensive experiments conducted on public legal and medical benchmarks reveal that BLADE significantly outperforms existing approaches. This shows the potential of BLADE as an effective and cost-efficient solution in adapting general LLMs for vertical domains.
