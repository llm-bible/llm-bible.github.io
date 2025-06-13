---
layout: publication
title: 'Customizing Language Models With Instance-wise Lora For Sequential Recommendation'
authors: Xiaoyu Kong, Jiancan Wu, An Zhang, Leheng Sheng, Hui Lin, Xiang Wang, Xiangnan He
conference: "38th Conference on Neural Information Processing Systems (NeurIPS 2024)"
year: 2024
bibkey: kong2024customizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10159"}
  - {name: "Code", url: "https://github.com/AkaliKong/iLoRA"}
tags: ['Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Sequential recommendation systems predict the next interaction item based on
users' past interactions, aligning recommendations with individual preferences.
Leveraging the strengths of Large Language Models (LLMs) in knowledge
comprehension and reasoning, recent approaches are eager to apply LLMs to
sequential recommendation. A common paradigm is converting user behavior
sequences into instruction data, and fine-tuning the LLM with
parameter-efficient fine-tuning (PEFT) methods like Low-Rank Adaption (LoRA).
However, the uniform application of LoRA across diverse user behaviors is
insufficient to capture individual variability, resulting in negative transfer
between disparate sequences. To address these challenges, we propose
Instance-wise LoRA (iLoRA). We innovatively treat the sequential recommendation
task as a form of multi-task learning, integrating LoRA with the Mixture of
Experts (MoE) framework. This approach encourages different experts to capture
various aspects of user behavior. Additionally, we introduce a sequence
representation guided gate function that generates customized expert
participation weights for each user sequence, which allows dynamic parameter
adjustment for instance-wise recommendations. In sequential recommendation,
iLoRA achieves an average relative improvement of 11.4% over basic LoRA in the
hit ratio metric, with less than a 1% relative increase in trainable
parameters. Extensive experiments on three benchmark datasets demonstrate the
effectiveness of iLoRA, highlighting its superior performance compared to
existing methods in mitigating negative transfer and improving recommendation
accuracy. Our data and code are available at
https://github.com/AkaliKong/iLoRA.
