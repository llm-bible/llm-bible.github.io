---
layout: publication
title: Hd45;eval Aligning Large Language Model Evaluators Through Hierarchical Criteria Decomposition
authors: Liu Yuxuan, Yang Tianchi, Huang Shaohan, Zhang Zihan, Huang Haizhen, Wei Furu, Deng Weiwei, Sun Feng, Zhang Qi
conference: "Arxiv"
year: 2024
bibkey: liu2024hd
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.15754"}
tags: ['Efficiency And Optimization', 'Ethics And Bias', 'Interpretability And Explainability', 'Prompting', 'Pruning', 'RAG', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have emerged as a promising alternative to expensive human evaluations. However the alignment and coverage of LLM45;based evaluations are often limited by the scope and potential bias of the evaluation prompts and criteria. To address this challenge we propose HD45;Eval a novel framework that iteratively aligns LLM45;based evaluators with human preference via Hierarchical Criteria Decomposition. HD45;Eval inherits the essence from the evaluation mindset of human experts and enhances the alignment of LLM45;based evaluators by decomposing a given evaluation task into finer45;grained criteria aggregating them according to estimated human preferences pruning insignificant criteria with attribution and further decomposing significant criteria. By integrating these steps within an iterative alignment training process we obtain a hierarchical decomposition of criteria that comprehensively captures aspects of natural language at multiple levels of granularity. Implemented as a white box the human preference45;guided aggregator is efficient to train and more explainable than relying solely on prompting and its independence from model parameters makes it applicable to closed45;source LLMs. Extensive experiments on three evaluation domains demonstrate the superiority of HD45;Eval in further aligning state45;of45;the45;art evaluators and providing deeper insights into the explanation of evaluation results and the task itself.
