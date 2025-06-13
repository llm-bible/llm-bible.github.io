---
layout: publication
title: 'LMCD: Language Models Are Zeroshot Cognitive Diagnosis Learners'
authors: Yu He, Zihan Yao, Chentao Song, Tianyu Qi, Jun Liu, Ming Li, Qing Huang
conference: "Arxiv"
year: 2025
bibkey: he2025language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21239"}
  - {name: "Code", url: "https://github.com/TAL-auroraX/LMCD"}
tags: ['Transformer', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Attention Mechanism', 'Has Code']
---
Cognitive Diagnosis (CD) has become a critical task in AI-empowered education, supporting personalized learning by accurately assessing students' cognitive states. However, traditional CD models often struggle in cold-start scenarios due to the lack of student-exercise interaction data. Recent NLP-based approaches leveraging pre-trained language models (PLMs) have shown promise by utilizing textual features but fail to fully bridge the gap between semantic understanding and cognitive profiling. In this work, we propose Language Models as Zeroshot Cognitive Diagnosis Learners (LMCD), a novel framework designed to handle cold-start challenges by harnessing large language models (LLMs). LMCD operates via two primary phases: (1) Knowledge Diffusion, where LLMs generate enriched contents of exercises and knowledge concepts (KCs), establishing stronger semantic links; and (2) Semantic-Cognitive Fusion, where LLMs employ causal attention mechanisms to integrate textual information and student cognitive states, creating comprehensive profiles for both students and exercises. These representations are efficiently trained with off-the-shelf CD models. Experiments on two real-world datasets demonstrate that LMCD significantly outperforms state-of-the-art methods in both exercise-cold and domain-cold settings. The code is publicly available at https://github.com/TAL-auroraX/LMCD
