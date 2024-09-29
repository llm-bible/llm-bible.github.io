---
layout: publication
title: Transfer Learning Of Language45;independent End45;to45;end ASR With Language Model Fusion
authors: Inaguma Hirofumi, Cho Jaejin, Baskar Murali Karthick, Kawahara Tatsuya, Watanabe Shinji
conference: "Arxiv"
year: 2018
bibkey: inaguma2018transfer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1811.02134"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Merging', 'Model Architecture', 'Tools']
---
This work explores better adaptation methods to low45;resource languages using an external language model (LM) under the framework of transfer learning. We first build a language45;independent ASR system in a unified sequence45;to45;sequence (S2S) architecture with a shared vocabulary among all languages. During adaptation we perform LM fusion transfer where an external LM is integrated into the decoder network of the attention45;based S2S model in the whole adaptation stage to effectively incorporate linguistic context of the target language. We also investigate various seed models for transfer learning. Experimental evaluations using the IARPA BABEL data set show that LM fusion transfer improves performances on all target five languages compared with simple transfer learning when the external text data is available. Our final system drastically reduces the performance gap from the hybrid systems.
