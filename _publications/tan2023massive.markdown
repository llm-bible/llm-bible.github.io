---
layout: publication
title: Massive Editing For Large Language Models Via Meta Learning
authors: Tan Chenmien, Zhang Ge, Fu Jie
conference: "Arxiv"
year: 2023
bibkey: tan2023massive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.04661"}
  - {name: "Code", url: "https://github.com/ChenmienTan/malmen"}
tags: ['Applications', 'BERT', 'GPT', 'Has Code', 'Model Architecture', 'Training Techniques']
---
While large language models (LLMs) have enabled learning knowledge from the pre45;training corpora the acquired knowledge may be fundamentally incorrect or outdated over time which necessitates rectifying the knowledge of the language model (LM) after the training. A promising approach involves employing a hyper45;network to generate parameter shift whereas existing hyper45;networks suffer from inferior scalability in synchronous editing operation amount. To mitigate the problem we propose the MAssive Language Model Editing Network (MALMEN) which formulates the parameter shift aggregation as the least square problem subsequently updating the LM parameters using the normal equation. To accommodate editing multiple facts simultaneously with limited memory budgets we separate the computation on the hyper45;network and LM enabling arbitrary batch size on both neural networks. Our method is evaluated by editing up to thousands of facts on LMs with different architectures i.e. BERT45;base GPT45;2 T545;XL (2.8B) and GPT45;J (6B) across various knowledge45;intensive NLP tasks i.e. closed book fact45;checking and question answering. Remarkably MALMEN is capable of editing hundreds of times more facts than strong baselines with the identical hyper45;network architecture and outperforms editor specifically designed for GPT. Our code is available at https://github.com/ChenmienTan/malmen.
