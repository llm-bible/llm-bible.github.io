---
layout: publication
title: Labrador Exploring The Limits Of Masked Language Modeling For Laboratory Data
authors: Bellamy David R., Kumar Bhawesh, Wang Cindy, Beam Andrew
conference: "Arxiv"
year: 2023
bibkey: bellamy2023exploring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.11502"}
tags: ['BERT', 'Fine Tuning', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
In this work we introduce Labrador a pre45;trained Transformer model for laboratory data. Labrador and BERT were pre45;trained on a corpus of 100 million lab test results from electronic health records (EHRs) and evaluated on various downstream outcome prediction tasks. Both models demonstrate mastery of the pre45;training task but neither consistently outperform XGBoost on downstream supervised tasks. Our ablation studies reveal that transfer learning shows limited effectiveness for BERT and achieves marginal success with Labrador. We explore the reasons for the failure of transfer learning and suggest that the data generating process underlying each patient cannot be characterized sufficiently using labs alone among other factors. We encourage future work to focus on joint modeling of multiple EHR data categories and to include tree45;based baselines in their evaluations.
