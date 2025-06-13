---
layout: publication
title: 'Rethinking Text-based Protein Understanding: Retrieval Or LLM?'
authors: Juntong Wu, Zijing Liu, He Cao, Hao Li, Bin Feng, Zishan Shu, Ke Yu, Li Yuan, Yu Li
conference: "Arxiv"
year: 2025
bibkey: wu2025rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20354"}
  - {name: "Code", url: "https://github.com/IDEA-XL/RAPM"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Pretraining Methods']
---
In recent years, protein-text models have gained significant attention for their potential in protein generation and understanding. Current approaches focus on integrating protein-related knowledge into large language models through continued pretraining and multi-modal alignment, enabling simultaneous comprehension of textual descriptions and protein sequences. Through a thorough analysis of existing model architectures and text-based protein understanding benchmarks, we identify significant data leakage issues present in current benchmarks. Moreover, conventional metrics derived from natural language processing fail to accurately assess the model's performance in this domain. To address these limitations, we reorganize existing datasets and introduce a novel evaluation framework based on biological entities. Motivated by our observation, we propose a retrieval-enhanced method, which significantly outperforms fine-tuned LLMs for protein-to-text generation and shows accuracy and efficiency in training-free scenarios. Our code and data can be seen at https://github.com/IDEA-XL/RAPM.
