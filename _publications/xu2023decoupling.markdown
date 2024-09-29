---
layout: publication
title: Rewoo Decoupling Reasoning From Observations For Efficient Augmented Language Models
authors: Xu Binfeng, Peng Zhiyuan, Lei Bowen, Mukherjee Subhabrata, Liu Yuchen, Xu Dongkuan
conference: "Arxiv"
year: 2023
bibkey: xu2023decoupling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.18323"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Security', 'Tools', 'Training Techniques']
---
Augmented Language Models (ALMs) blend the reasoning capabilities of Large Language Models (LLMs) with tools that allow for knowledge retrieval and action execution. Existing ALM systems trigger LLM thought processes while pulling observations from these tools in an interleaved fashion. Specifically an LLM reasons to call an external tool gets halted to fetch the tools response and then decides the next action based on all preceding response tokens. Such a paradigm though straightforward and easy to implement often leads to huge computation complexity from redundant prompts and repeated execution. This study addresses such challenges for the first time proposing a modular paradigm ReWOO (Reasoning WithOut Observation) that detaches the reasoning process from external observations thus significantly reducing token consumption. Comprehensive evaluations across six public NLP benchmarks and a curated dataset reveal consistent performance enhancements with our proposed methodology. Notably ReWOO achieves 5x token efficiency and 437; accuracy improvement on HotpotQA a multi-step reasoning benchmark. Furthermore ReWOO demonstrates robustness under tool-failure scenarios. Beyond prompt efficiency decoupling parametric modules from non-parametric tool calls enables instruction fine-tuning to offload LLMs into smaller language models thus substantially reducing model parameters. Our illustrative work offloads reasoning ability from 175B GPT3.5 into 7B LLaMA demonstrating the significant potential for truly efficient and scalable ALM systems.
