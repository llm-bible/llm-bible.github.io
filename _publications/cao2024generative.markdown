---
layout: publication
title: Genrec: Generative Sequential Recommendation With Large Language Models
authors: Cao Panfeng, Lio Pietro
conference: "Arxiv"
year: 2024
bibkey: cao2024generative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.21191"}
tags: ['Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Sequential recommendation is a task to capture hidden user preferences from historical user item interaction data and recommend next items for the user. Significant progress has been made in this domain by leveraging classification based learning methods. Inspired by the recent paradigm of pretrain prompt and predict in NLP we consider sequential recommendation as a sequence to sequence generation task and propose a novel model named Generative Recommendation (GenRec). Unlike classification based models that learn explicit user and item representations GenRec utilizes the sequence modeling capability of Transformer and adopts the masked item prediction objective to effectively learn the hidden bidirectional sequential patterns. Different from existing generative sequential recommendation models GenRec does not rely on manually designed hard prompts. The input to GenRec is textual user item sequence and the output is top ranked next items. Moreover GenRec is lightweight and requires only a few hours to train effectively in low-resource settings making it highly applicable to real-world scenarios and helping to democratize large language models in the sequential recommendation domain. Our extensive experiments have demonstrated that GenRec generalizes on various public real-world datasets and achieves state-of-the-art results. Our experiments also validate the effectiveness of the the proposed masked item prediction objective that improves the model performance by a large margin.
