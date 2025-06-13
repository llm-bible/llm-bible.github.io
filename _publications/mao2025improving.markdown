---
layout: publication
title: 'LIFT: Improving Long Context Understanding Of Large Language Models Through Long Input Fine-tuning'
authors: Yansheng Mao, Yufei Xu, Jiaqi Li, Fanxu Meng, Haotong Yang, Zilong Zheng, Xiyuan Wang, Muhan Zhang
conference: "Arxiv"
year: 2025
bibkey: mao2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14644"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'In-Context Learning', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Attention Mechanism']
---
Long context understanding remains challenging for large language models due
to their limited context windows. This paper presents Long Input Fine-Tuning
(LIFT), a novel framework for long-context modeling that can improve the
long-context performance of arbitrary (short-context) LLMs by dynamically
adapting model parameters based on the long input. Importantly, LIFT, rather
than endlessly extending the context window size to accommodate increasingly
longer inputs in context, chooses to store and absorb the long input in
parameter. By fine-tuning the long input into model parameters, LIFT allows
short-context LLMs to answer questions even when the required information is
not provided in the context during inference. Furthermore, to enhance LIFT
performance while maintaining the original in-context learning (ICL)
capabilities, we introduce Gated Memory, a specialized attention adapter that
automatically balances long input memorization and ICL. We provide a
comprehensive analysis of the strengths and limitations of LIFT on long context
understanding, offering valuable directions for future research.
