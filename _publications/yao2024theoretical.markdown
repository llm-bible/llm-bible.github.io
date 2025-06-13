---
layout: publication
title: 'Theoretical Insights Into Fine-tuning Attention Mechanism: Generalization And Optimization'
authors: Xinhao Yao, Hongjin Qian, Xiaolin Hu, Gengze Xu, Wei Liu, Jian Luan, Bin Wang, Yong Liu
conference: "Arxiv"
year: 2024
bibkey: yao2024theoretical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02247"}
tags: ['Fine-Tuning', 'Transformer', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Large Language Models (LLMs), built on Transformer architectures, exhibit remarkable generalization across a wide range of tasks. However, fine-tuning these models for specific tasks remains resource-intensive due to their extensive parameterization. In this paper, we explore two remarkable phenomena related to the attention mechanism during the fine-tuning of LLMs (where \\(\mathbf\{W\}_q\\), \\(\mathbf\{W\}_k\\), and \\(\mathbf\{W\}_v\\) denote the weights of the query, key, and value layers, respectively). The first phenomenon, termed "Unequal Importance of Attention Matrices", highlights the impact of fine-tuning different weight matrices. It shows that optimizing the \\(\mathbf\{W\}_v\\) matrix yields significantly better performance than optimizing the \\(\mathbf\{W\}_k\\) matrix. Fine-tuning only the \\(\mathbf\{W\}_q\\) and \\(\mathbf\{W\}_v\\) matrices is computationally efficient while delivering results comparable to, or even better than fine-tuning all three matrices (\\(\mathbf\{W\}_q\\), \\(\mathbf\{W\}_k\\), and \\(\mathbf\{W\}_v\\)). The second phenomenon,"Attention Matrices with Customized Learning Rate Lead to Better Convergence", emphasizes the importance of assigning distinct learning rates to these matrices. Specifically, a higher learning rate for the \\(\mathbf\{W\}_v\\) matrix compared to \\(\mathbf\{W\}_q\\) and \\(\mathbf\{W\}_k\\) accelerates convergence and improves performance. Building on these insights, we propose a new strategy that improves fine-tuning efficiency in terms of both storage and time. Experimental results on benchmark datasets validate the effectiveness of this approach, supporting our theoretical findings. Our analysis lays the theoretical groundwork for configuring and improving algorithms in LLMs fine-tuning.
