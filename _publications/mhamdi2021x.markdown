---
layout: publication
title: 'X-METRA-ADA: Cross-lingual Meta-transfer Learning Adaptation To Natural Language Understanding And Question Answering'
authors: Meryem M'hamdi, Doo Soon Kim, Franck Dernoncourt, Trung Bui, Xiang Ren, Jonathan May
conference: "Arxiv"
year: 2021
bibkey: mhamdi2021x
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.09696"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'BERT']
---
Multilingual models, such as M-BERT and XLM-R, have gained increasing
popularity, due to their zero-shot cross-lingual transfer learning
capabilities. However, their generalization ability is still inconsistent for
typologically diverse languages and across different benchmarks. Recently,
meta-learning has garnered attention as a promising technique for enhancing
transfer learning under low-resource scenarios: particularly for cross-lingual
transfer in Natural Language Understanding (NLU). In this work, we propose
X-METRA-ADA, a cross-lingual MEta-TRAnsfer learning ADAptation approach for
NLU. Our approach adapts MAML, an optimization-based meta-learning approach, to
learn to adapt to new languages. We extensively evaluate our framework on two
challenging cross-lingual NLU tasks: multilingual task-oriented dialog and
typologically diverse question answering. We show that our approach outperforms
naive fine-tuning, reaching competitive performance on both tasks for most
languages. Our analysis reveals that X-METRA-ADA can leverage limited data for
faster adaptation.
