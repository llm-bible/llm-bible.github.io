---
layout: publication
title: Multi-task Instruction Tuning Of Llama For Specific Scenarios A Preliminary Study On Writing Assistance
authors: Zhang Yue, Cui Leyang, Cai Deng, Huang Xinting, Fang Tao, Bi Wei
conference: "Arxiv"
year: 2023
bibkey: zhang2023multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13225"}
tags: ['Attention Mechanism', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Proprietary Large Language Models (LLMs) such as ChatGPT have garnered significant attention due to their exceptional capabilities in handling a diverse range of tasks. Recent studies demonstrate that open-sourced smaller foundational models such as 7B-size LLaMA can also display remarkable proficiency in tackling diverse tasks when fine-tuned using instruction-driven data. In this work we investigate a practical problem setting where the primary focus is on one or a few particular tasks rather than general-purpose instruction following and explore whether LLMs can be beneficial and further improved for such targeted scenarios. We choose the writing-assistant scenario as the testbed which includes seven writing tasks. We collect training data for these tasks reframe them in an instruction-following format and subsequently refine the LLM specifically LLaMA via instruction tuning. Experimental results show that fine-tuning LLaMA on writing instruction data significantly improves its ability on writing tasks. We also conduct more experiments and analyses to offer insights for future work on effectively fine-tuning LLaMA for specific scenarios. Finally we initiate a discussion regarding the necessity of employing LLMs for only one targeted task taking into account the efforts required for tuning and the resources consumed during deployment.
