---
layout: publication
title: Llavolta Efficient Multi-modal Models Via Stage-wise Visual Context Compression
authors: Chen Jieneng, Ye Luoxin, He Ju, Wang Zhao-yang, Khashabi Daniel, Yuille Alan
conference: "Arxiv"
year: 2024
bibkey: chen2024llavolta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.20092"}
  - {name: "Code", url: "https://github.com/Beckschen/LLaVolta"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
While significant advancements have been made in compressed representations for text embeddings in large language models (LLMs) the compression of visual tokens in large multi-modal models (LMMs) has remained a largely overlooked area. In this work we present the study on the analysis of redundancy concerning visual tokens and efficient training within these models. Our initial experiments show that eliminating up to 7037; of visual tokens at the testing stage by simply average pooling only leads to a minimal 337; reduction in visual question answering accuracy on the GQA benchmark indicating significant redundancy in visual context. Addressing this we introduce Visual Context Compressor which reduces the number of visual tokens during training to enhance training efficiency without sacrificing performance. To minimize information loss caused by the compression on visual tokens while maintaining training efficiency we develop LLaVolta as a lite training scheme. LLaVolta incorporates stage-wise visual context compression to progressively compress the visual tokens from heavily to lightly and finally no compression at the end of training yielding no loss of information when testing. Extensive experiments demonstrate that our approach enhances the performance of MLLMs in both image-language and video-language understanding while also significantly cutting training costs. Code is available at https://github.com/Beckschen/LLaVolta
