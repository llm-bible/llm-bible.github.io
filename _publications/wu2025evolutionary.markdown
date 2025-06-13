---
layout: publication
title: 'EVOREFUSE: Evolutionary Prompt Optimization For Evaluation And Mitigation Of LLM Over-refusal To Pseudo-malicious Instructions'
authors: Xiaorui Wu, Xiaofeng Mao, Xin Zhang, Fei Li, Chong Teng, Yuxiang Peng, Li Zheng, Donghong Ji, Zhuang Li
conference: "Arxiv"
year: 2025
bibkey: wu2025evolutionary
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23473"}
tags: ['Responsible AI', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
Large language models (LLMs) frequently refuse to respond to pseudo-malicious instructions: semantically harmless input queries triggering unnecessary LLM refusals due to conservative safety alignment, significantly impairing user experience. Collecting such instructions is crucial for evaluating and mitigating over-refusals, but existing instruction curation methods, like manual creation or instruction rewriting, either lack scalability or fail to produce sufficiently diverse and effective refusal-inducing prompts. To address these limitations, we introduce EVOREFUSE, a prompt optimization approach that generates diverse pseudo-malicious instructions consistently eliciting confident refusals across LLMs. EVOREFUSE employs an evolutionary algorithm exploring the instruction space in more diverse directions than existing methods via mutation strategies and recombination, and iteratively evolves seed instructions to maximize evidence lower bound on LLM refusal probability. Using EVOREFUSE, we create two novel datasets: EVOREFUSE-TEST, a benchmark of 582 pseudo-malicious instructions that outperforms the next-best benchmark with 140.41% higher average refusal triggering rate across 9 LLMs, 34.86% greater lexical diversity, and 40.03% improved LLM response confidence scores; and EVOREFUSE-ALIGN, which provides 3,000 pseudo-malicious instructions with responses for supervised and preference-based alignment training. LLAMA3.1-8B-INSTRUCT supervisedly fine-tuned on EVOREFUSE-ALIGN achieves up to 14.31% fewer over-refusals than models trained on the second-best alignment dataset, without compromising safety. Our analysis with EVOREFUSE-TEST reveals models trigger over-refusals by overly focusing on sensitive keywords while ignoring broader context.
