---
layout: publication
title: 'Transferring Backdoors Between Large Language Models By Knowledge Distillation'
authors: Cheng Pengzhou, Wu Zongru, Ju Tianjie, Du Wei, Liu Zhuosheng Zhang Gongshen
conference: "Arxiv"
year: 2024
bibkey: cheng2024transferring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09878"}
tags: ['Attention Mechanism', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Security']
---
Backdoor Attacks have been a serious vulnerability against Large Language Models (LLMs). However, previous methods only reveal such risk in specific models, or present tasks transferability after attacking the pre-trained phase. So, how risky is the model transferability of a backdoor attack? In this paper, we focus on whether existing mini-LLMs may be unconsciously instructed in backdoor knowledge by poisoned teacher LLMs through knowledge distillation (KD). Specifically, we propose ATBA, an adaptive transferable backdoor attack, which can effectively distill the backdoor of teacher LLMs into small models when only executing clean-tuning. We first propose the Target Trigger Generation (TTG) module that filters out a set of indicative trigger candidates from the token list based on cosine similarity distribution. Then, we exploit a shadow model to imitate the distilling process and introduce an Adaptive Trigger Optimization (ATO) module to realize a gradient-based greedy feedback to search optimal triggers. Extensive experiments show that ATBA generates not only positive guidance for student models but also implicitly transfers backdoor knowledge. Our attack is robust and stealthy, with over 80&#37; backdoor transferability, and hopes the attention of security.
