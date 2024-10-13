---
layout: publication
title: 'Cheap And Quick: Efficient Vision-language Instruction Tuning For Large Language Models'
authors: Luo Gen, Zhou Yiyi, Ren Tianhe, Chen Shengxin, Sun Xiaoshuai, Ji Rongrong
conference: "Arxiv"
year: 2023
bibkey: luo2023cheap
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15023"}
  - {name: "Code", url: "https://luogen1996.github.io/lavin"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Multimodal Models', 'Training Techniques']
---
Recently, growing interest has been aroused in extending the multimodal
capability of large language models (LLMs), e.g., vision-language (VL)
learning, which is regarded as the next milestone of artificial general
intelligence. However, existing solutions are prohibitively expensive, which
not only need to optimize excessive parameters, but also require another
large-scale pre-training before VL instruction tuning. In this paper, we
propose a novel and affordable solution for the effective VL adaption of LLMs,
called Mixture-of-Modality Adaptation (MMA). Instead of using large neural
networks to connect the image encoder and LLM, MMA adopts lightweight modules,
i.e., adapters, to bridge the gap between LLMs and VL tasks, which also enables
the joint optimization of the image and language models. Meanwhile, MMA is also
equipped with a routing algorithm to help LLMs achieve an automatic shift
between single- and multi-modal instructions without compromising their ability
of natural language understanding. To validate MMA, we apply it to a recent LLM
called LLaMA and term this formed large vision-language instructed model as
LaVIN. To validate MMA and LaVIN, we conduct extensive experiments under two
setups, namely multimodal science question answering and multimodal dialogue.
The experimental results not only demonstrate the competitive performance and
the superior training efficiency of LaVIN than existing multimodal LLMs, but
also confirm its great potential as a general-purpose chatbot. More
importantly, the actual expenditure of LaVIN is extremely cheap, e.g., only 1.4
training hours with 3.8M trainable parameters, greatly confirming the
effectiveness of MMA. Our project is released at
https://luogen1996.github.io/lavin.
