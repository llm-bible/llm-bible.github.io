---
layout: publication
title: 'ALPS: Attention Localization And Pruning Strategy For Efficient Alignment Of Large Language Models'
authors: Hao Chen, Haoze Li, Zhiqing Xiao, Lirong Gao, Qi Zhang, Xiaomeng Hu, Ningtao Wang, Xing Fu, Junbo Zhao
conference: "Arxiv"
year: 2025
bibkey: chen2025attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18799"}
  - {name: "Code", url: "https://github.com/VoiceBeer/ALPS"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Pruning', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Attention Mechanism']
---
Aligning general-purpose large language models (LLMs) to downstream tasks often incurs significant training adjustment costs. Prior research has explored various avenues to enhance alignment efficiency, primarily through minimal-data training or data-driven activations to identify key attention heads. However, these approaches inherently introduce data dependency, which hinders generalization and reusability. To address this issue and enhance model alignment efficiency, we propose the \textit\{\textbf\{A\}ttention \textbf\{L\}ocalization and \textbf\{P\}runing \textbf\{S\}trategy (\textbf\{ALPS\})\}, an efficient algorithm that localizes the most task-sensitive attention heads and prunes by restricting attention training updates to these heads, thereby reducing alignment costs. Experimental results demonstrate that our method activates only \textbf\{10%\} of attention parameters during fine-tuning while achieving a \textbf\{2%\} performance improvement over baselines on three tasks. Moreover, the identified task-specific heads are transferable across datasets and mitigate knowledge forgetting. Our work and findings provide a novel perspective on efficient LLM alignment. The code is available at https://github.com/VoiceBeer/ALPS.
