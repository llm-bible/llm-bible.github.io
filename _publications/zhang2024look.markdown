---
layout: publication
title: Look Ahead Or Look Around A Theoretical Comparison Between Autoregressive And Masked Pretraining
authors: Zhang Qi, Du Tianqi, Huang Haotian, Wang Yifei, Wang Yisen
conference: "Arxiv"
year: 2024
bibkey: zhang2024look
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00935"}
  - {name: "Code", url: "https://github.com/PKU-ML/LookAheadLookAround"}
tags: ['GPT', 'Has Code', 'Pretraining Methods', 'RAG', 'Tools', 'Training Techniques']
---
In recent years the rise of generative self-supervised learning (SSL) paradigms has exhibited impressive performance across visual language and multi-modal domains. While the varied designs of generative SSL objectives lead to distinct properties in downstream tasks a theoretical understanding of these differences remains largely unexplored. In this paper we establish the first theoretical comparisons between two leading generative SSL paradigms autoregressive SSL and masked SSL. Through establishing theoretical frameworks we elucidate the strengths and limitations of autoregressive and masked SSL within the primary evaluation tasks of classification and content generation. Our findings demonstrate that in classification tasks the flexibility of targeted tokens in masked SSL fosters more inter-sample connections compared to the fixed position of target tokens in autoregressive SSL which yields superior clustering performance. In content generation tasks the misalignment between the flexible lengths of test samples and the fixed length of unmasked texts in masked SSL (vs. flexible lengths of conditional texts in autoregressive SSL) hinders its generation performance. To leverage each others strengths and mitigate weaknesses we propose diversity-enhanced autoregressive and variable-length masked objectives which substantially improve the classification performance of autoregressive SSL and the generation performance of masked SSL. Code is available at https://github.com/PKU-ML/LookAheadLookAround.
