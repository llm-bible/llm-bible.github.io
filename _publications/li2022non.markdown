---
layout: publication
title: ELMER&#58; A Non-autoregressive Pre-trained Language Model For Efficient And Effective Text Generation
authors: Li Junyi, Tang Tianyi, Zhao Wayne Xin, Nie Jian-yun, Wen Ji-rong
conference: "Arxiv"
year: 2022
bibkey: li2022non
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.13304"}
tags: ['Applications', 'Efficiency And Optimization', 'GPT', 'Language Modeling', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
We study the text generation task under the approach of pre-trained language models (PLMs). Typically an auto-regressive (AR) method is adopted for generating texts in a token-by-token manner. Despite many advantages of AR generation it usually suffers from inefficient inference. Therefore non-autoregressive (NAR) models are proposed to generate all target tokens simultaneously. However NAR models usually generate texts of lower quality due to the absence of token dependency in the output text. In this paper we propose ELMER an efficient and effective PLM for NAR text generation to explicitly model the token dependency during NAR generation. By leveraging the early exit technique ELMER enables the token generations at different layers according to their prediction confidence (a more confident token will exit at a lower layer). Besides we propose a novel pre-training objective Layer Permutation Language Modeling to pre-train ELMER by permuting the exit layer for each token in sequences. Experiments on three text generation tasks show that ELMER significantly outperforms NAR models and further narrows the performance gap with AR PLMs ((eg) ELMER (29.92) vs BART (30.61) ROUGE-L in XSUM) while achieving over 10 times inference speedup.
