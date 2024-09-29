---
layout: publication
title: Emulated Disalignment Safety Alignment For Large Language Models May Backfire!
authors: Zhou Zhanhui, Liu Jie, Dong Zhichen, Liu Jiaheng, Yang Chao, Ouyang Wanli, Qiao Yu
conference: "Arxiv"
year: 2024
bibkey: zhou2024emulated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12343"}
  - {name: "Code", url: "https://github.com/ZHZisZZ/emulated&#45;disalignment"}
tags: ['Has Code', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Training Techniques']
---
Large language models (LLMs) undergo safety alignment to ensure safe conversations with humans. However this paper introduces a training45;free attack method capable of reversing safety alignment converting the outcomes of stronger alignment into greater potential for harm by accessing only LLM output token distributions. Specifically our method achieves this reversal by contrasting the output token distribution of a safety45;aligned language model (e.g. Llama45;245;chat) against its pre45;trained version (e.g. Llama45;2) so that the token predictions are shifted towards the opposite direction of safety alignment. We name this method emulated disalignment (ED) because sampling from this contrastive distribution provably emulates the result of fine45;tuning to minimize a safety reward. Our experiments with ED across three evaluation datasets and four model families (Llama45;1 Llama45;2 Mistral and Alpaca) show that ED doubles the harmfulness of pre45;trained models and outperforms strong baselines achieving the highest harmful rates in 43 out of 48 evaluation subsets by a large margin. Eventually given EDs reliance on language model output token distributions which particularly compromises open45;source models our findings highlight the need to reassess the open accessibility of language models even if they have been safety45;aligned. Code is available at https://github.com/ZHZisZZ/emulated&#45;disalignment.
