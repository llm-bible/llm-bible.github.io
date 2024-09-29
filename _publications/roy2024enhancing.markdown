---
layout: publication
title: Enhancing Low45;resource NMT With A Multilingual Encoder And Knowledge Distillation A Case Study
authors: Roy Aniruddha, Ray Pretam, Maheshwari Ayush, Sarkar Sudeshna, Goyal Pawan
conference: "Arxiv"
year: 2024
bibkey: roy2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.06538"}
  - {name: "Code", url: "https://github.com/raypretam/Two&#45;step&#45;low&#45;res&#45;NMT"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Has Code', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Neural Machine Translation (NMT) remains a formidable challenge especially when dealing with low45;resource languages. Pre45;trained sequence45;to45;sequence (seq2seq) multi45;lingual models such as mBART45;50 have demonstrated impressive performance in various low45;resource NMT tasks. However their pre45;training has been confined to 50 languages leaving out support for numerous low45;resource languages particularly those spoken in the Indian subcontinent. Expanding mBART45;50s language support requires complex pre45;training risking performance decline due to catastrophic forgetting. Considering these expanding challenges this paper explores a framework that leverages the benefits of a pre45;trained language model along with knowledge distillation in a seq2seq architecture to facilitate translation for low45;resource languages including those not covered by mBART45;50. The proposed framework employs a multilingual encoder45;based seq2seq model as the foundational architecture and subsequently uses complementary knowledge distillation techniques to mitigate the impact of imbalanced training. Our framework is evaluated on three low45;resource Indic languages in four Indic45;to45;Indic directions yielding significant BLEU45;4 and chrF improvements over baselines. Further we conduct human evaluation to confirm effectiveness of our approach. Our code is publicly available at https://github.com/raypretam/Two&#45;step&#45;low&#45;res&#45;NMT.
