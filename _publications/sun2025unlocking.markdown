---
layout: publication
title: 'Solopo: Unlocking Long-context Capabilities In Llms Via Short-to-long Preference Optimization'
authors: Huashan Sun, Shengyi Liao, Yansen Han, Yu Bai, Yang Gao, Cheng Fu, Weizhou Shen, Fanqi Wan, Ming Yan, Ji Zhang, Fei Huang
conference: "Arxiv"
year: 2025
bibkey: sun2025unlocking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.11166"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods']
---
Despite advances in pretraining with extended context lengths, large language models (LLMs) still face challenges in effectively utilizing real-world long-context information, primarily due to insufficient long-context alignment caused by data quality issues, training inefficiencies, and the lack of well-designed optimization objectives. To address these limitations, we propose a framework named \\(\textbf\{S\}\\)h\\(\textbf\{o\}\\)rt-to-\\(\textbf\{Lo\}\\)ng \\(\textbf\{P\}\\)reference \\(\textbf\{O\}\\)ptimization (\\(\textbf\{SoLoPO\}\\)), decoupling long-context preference optimization (PO) into two components: short-context PO and short-to-long reward alignment (SoLo-RA), supported by both theoretical and empirical evidence. Specifically, short-context PO leverages preference pairs sampled from short contexts to enhance the model's contextual knowledge utilization ability. Meanwhile, SoLo-RA explicitly encourages reward score consistency utilization for the responses when conditioned on both short and long contexts that contain identical task-relevant information. This facilitates transferring the model's ability to handle short contexts into long-context scenarios. SoLoPO is compatible with mainstream preference optimization algorithms, while substantially improving the efficiency of data construction and training processes. Experimental results show that SoLoPO enhances all these algorithms with respect to stronger length and domain generalization abilities across various long-context benchmarks, while achieving notable improvements in both computational and memory efficiency.
