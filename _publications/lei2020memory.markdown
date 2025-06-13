---
layout: publication
title: 'MART: Memory-augmented Recurrent Transformer For Coherent Video Paragraph Captioning'
authors: Jie Lei, Liwei Wang, Yelong Shen, Dong Yu, Tamara L. Berg, Mohit Bansal
conference: "Arxiv"
year: 2020
bibkey: lei2020memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.05402"}
  - {name: "Code", url: "https://github.com/jayleicn/recurrent-transformer"}
tags: ['Model Architecture', 'RAG', 'Pretraining Methods', 'Transformer', 'Has Code']
---
Generating multi-sentence descriptions for videos is one of the most
challenging captioning tasks due to its high requirements for not only visual
relevance but also discourse-based coherence across the sentences in the
paragraph. Towards this goal, we propose a new approach called Memory-Augmented
Recurrent Transformer (MART), which uses a memory module to augment the
transformer architecture. The memory module generates a highly summarized
memory state from the video segments and the sentence history so as to help
better prediction of the next sentence (w.r.t. coreference and repetition
aspects), thus encouraging coherent paragraph generation. Extensive
experiments, human evaluations, and qualitative analyses on two popular
datasets ActivityNet Captions and YouCookII show that MART generates more
coherent and less repetitive paragraph captions than baseline methods, while
maintaining relevance to the input video events. All code is available
open-source at: https://github.com/jayleicn/recurrent-transformer
