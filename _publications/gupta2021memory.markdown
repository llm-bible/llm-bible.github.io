---
layout: publication
title: Memory45;efficient Transformers Via Top45;k Attention
authors: Gupta Ankit, Dar Guy, Goodman Shaya, Ciprut David, Berant Jonathan
conference: "Arxiv"
year: 2021
bibkey: gupta2021memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.06899"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques', 'Transformer']
---
Following the success of dot45;product attention in Transformers numerous approximations have been recently proposed to address its quadratic complexity with respect to the input length. While these variants are memory and compute efficient it is not possible to directly use them with popular pre45;trained language models trained using vanilla attention without an expensive corrective pre45;training stage. In this work we propose a simple yet highly accurate approximation for vanilla attention. We process the queries in chunks and for each query compute the top45;k scores with respect to the keys. Our approach offers several advantages (a) its memory usage is linear in the input size similar to linear attention variants such as Performer and RFA (b) it is a drop45;in replacement for vanilla attention that does not require any corrective pre45;training and (c) it can also lead to significant memory savings in the feed45;forward layers after casting them into the familiar query45;key45;value framework. We evaluate the quality of top45;k approximation for multi45;head attention layers on the Long Range Arena Benchmark and for feed45;forward layers of T5 and UnifiedQA on multiple QA datasets. We show our approach leads to accuracy that is nearly45;identical to vanilla attention in multiple setups including training from scratch fine45;tuning and zero45;shot inference.
