---
layout: publication
title: 'Emphasising Structured Information: Integrating Abstract Meaning Representation Into Llms For Enhanced Open-domain Dialogue Evaluation'
authors: Yang Bohao, Zhao Kun, Tang Chen, Liu Dong, Zhan Liang, Lin Chenghua
conference: "Arxiv"
year: 2024
bibkey: yang2024emphasising
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.01129"}
  - {name: "Code", url: "https://github.com/Bernard-Yang/SIMAMR"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Has Code', 'Model Architecture', 'Prompting', 'Security', 'Tools']
---
Automatic open-domain dialogue evaluation has attracted increasing attention. Trainable evaluation metrics typically trained with true positive and randomly selected negative responses tend to assign higher scores to responses that share greater content similarity with a given context. However adversarial negative responses despite possessing high content similarity with the contexts are semantically different. Consequently existing evaluation metrics are not robust enough to evaluate such responses resulting in low correlations with human judgments. While recent studies have demonstrated the effectiveness of Large Language Models (LLMs) for open-domain dialogue evaluation they still face challenges in effectively handling adversarial negative examples. In this paper we propose an effective framework for open-domain dialogue evaluation which combines domain-specific language models (SLMs) enhanced with Abstract Meaning Representation (AMR) knowledge with LLMs. The SLMs can explicitly incorporate AMR graph information of the dialogue through a gating mechanism for enhanced dialogue semantic representation learning. Both the evaluation result from the SLMs and the AMR graph information are incorporated into the LLMs prompt for enhanced evaluation performance. Experimental results on open-domain dialogue evaluation tasks demonstrate the superiority of our method compared to a wide range of state-of-the-art baselines especially in discriminating adversarial negative responses. Our code and data are publicly available at https://github.com/Bernard-Yang/SIMAMR."
