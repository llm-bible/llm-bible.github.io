---
layout: publication
title: Sheared Llama Accelerating Language Model Pre45;training Via Structured Pruning
authors: Xia Mengzhou, Gao Tianyu, Zeng Zhiyuan, Chen Danqi
conference: "Arxiv"
year: 2023
bibkey: xia2023sheared
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.06694"}
tags: ['Efficiency And Optimization', 'Pruning', 'RAG', 'Training Techniques']
---
The popularity of LLaMA (Touvron et al. 2023a;b) and other recently emerged moderate45;sized large language models (LLMs) highlights the potential of building smaller yet powerful LLMs. Regardless the cost of training such models from scratch on trillions of tokens remains high. In this work we study structured pruning as an effective means to develop smaller LLMs from pre45;trained larger models. Our approach employs two key techniques (1) targeted structured pruning which prunes a larger model to a specified target shape by removing layers heads and intermediate and hidden dimensions in an end45;to45;end manner and (2) dynamic batch loading which dynamically updates the composition of sampled data in each training batch based on varying losses across different domains. We demonstrate the efficacy of our approach by presenting the Sheared45;LLaMA series pruning the LLaMA245;7B model down to 1.3B and 2.7B parameters. Sheared45;LLaMA models outperform state45;of45;the45;art open45;source models of equivalent sizes such as Pythia INCITE OpenLLaMA and the concurrent TinyLlama models on a wide range of downstream and instruction tuning evaluations while requiring only 337; of compute compared to training such models from scratch. This work provides compelling evidence that leveraging existing LLMs with structured pruning is a far more cost45;effective approach for building competitive small45;scale LLMs
