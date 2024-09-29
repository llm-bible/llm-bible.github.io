---
layout: publication
title: Enhancing Low-resource NMT With A Multilingual Encoder And Knowledge Distillation: A Case Study
authors: Roy Aniruddha, Ray Pretam, Maheshwari Ayush, Sarkar Sudeshna, Goyal Pawan
conference: "Arxiv"
year: 2024
bibkey: roy2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.06538"}
  - {name: "Code", url: "https://github.com/raypretam/Two-step-low-res-NMT"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Neural Machine Translation (NMT) remains a formidable challenge especially when dealing with low-resource languages. Pre-trained sequence-to-sequence (seq2seq) multi-lingual models such as mBART-50 have demonstrated impressive performance in various low-resource NMT tasks. However their pre-training has been confined to 50 languages leaving out support for numerous low-resource languages particularly those spoken in the Indian subcontinent. Expanding mBART-50s language support requires complex pre-training risking performance decline due to catastrophic forgetting. Considering these expanding challenges this paper explores a framework that leverages the benefits of a pre-trained language model along with knowledge distillation in a seq2seq architecture to facilitate translation for low-resource languages including those not covered by mBART-50. The proposed framework employs a multilingual encoder-based seq2seq model as the foundational architecture and subsequently uses complementary knowledge distillation techniques to mitigate the impact of imbalanced training. Our framework is evaluated on three low-resource Indic languages in four Indic-to-Indic directions yielding significant BLEU-4 and chrF improvements over baselines. Further we conduct human evaluation to confirm effectiveness of our approach. Our code is publicly available at https://github.com/raypretam/Two-step-low-res-NMT."
