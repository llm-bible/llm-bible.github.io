---
layout: publication
title: 'On The Prunability Of Attention Heads In Multilingual BERT'
authors: Budhraja Aakriti, Pande Madhura, Kumar Pratyush, Khapra Mitesh M.
conference: "Arxiv"
year: 2021
bibkey: budhraja2021prunability
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2109.12683"}
tags: ['Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Large multilingual models, such as mBERT, have shown promise in crosslingual transfer. In this work, we employ pruning to quantify the robustness and interpret layer-wise importance of mBERT. On four GLUE tasks, the relative drops in accuracy due to pruning have almost identical results on mBERT and BERT suggesting that the reduced attention capacity of the multilingual models does not affect robustness to pruning. For the crosslingual task XNLI, we report higher drops in accuracy with pruning indicating lower robustness in crosslingual transfer. Also, the importance of the encoder layers sensitively depends on the language family and the pre-training corpus size. The top layers, which are relatively more influenced by fine-tuning, encode important information for languages similar to English (SVO) while the bottom layers, which are relatively less influenced by fine-tuning, are particularly important for agglutinative and low-resource languages.
