---
layout: publication
title: 'Unlocking Continual Learning Abilities In Language Models'
authors: Du Wenyu, Cheng Shuang, Luo Tongxu, Qiu Zihan, Huang Zeyu, Cheung Ka Chun, Cheng Reynold, Fu Jie
conference: "Arxiv"
year: 2024
bibkey: du2024unlocking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17245"}
  - {name: "Code", url: "https://github.com/wenyudu/MIGU}{this"}
tags: ['BERT', 'Ethics And Bias', 'Has Code', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Language models (LMs) exhibit impressive performance and generalization capabilities. However LMs struggle with the persistent challenge of catastrophic forgetting which undermines their long-term sustainability in continual learning (CL). Existing approaches usually address the issue by incorporating old task data or task-wise inductive bias into LMs. However old data and accurate task information are often unavailable or costly to collect hindering the availability of current CL approaches for LMs. To address this limitation we introduce () (()agn()tude-based ()radient ()pdating for continual learning) a rehearsal-free and task-label-free method that only updates the model parameters with large magnitudes of output in LMs linear layers. MIGU is based on our observation that the L1-normalized magnitude distribution of the output in LMs linear layers is different when the LM models deal with different task data. By imposing this simple constraint on the gradient update process we can leverage the inherent behaviors of LMs thereby unlocking their innate CL abilities. Our experiments demonstrate that MIGU is universally applicable to all three LM architectures (T5 RoBERTa and Llama2) delivering state-of-the-art or on-par performance across continual finetuning and continual pre-training settings on four CL benchmarks. For example MIGU brings a 15.237; average accuracy improvement over conventional parameter-efficient finetuning baselines in a 15-task CL benchmark. MIGU can also seamlessly integrate with all three existing CL types to further enhance performance. Code is available at hrefhttps://github.com/wenyudu/MIGU\}\{this https URL.
