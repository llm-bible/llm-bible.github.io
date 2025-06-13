---
layout: publication
title: 'Efficient Reasoning For Llms Through Speculative Chain-of-thought'
authors: Jikai Wang, Juntao Li, Jianye Hou, Bowen Yan, Lijun Wu, Min Zhang
conference: "Arxiv"
year: 2025
bibkey: wang2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.19095"}
  - {name: "Code", url: "https://github.com/Jikai0Wang/Speculative_CoT"}
tags: ['Efficiency and Optimization', 'RAG', 'Model Architecture', 'Attention Mechanism', 'Has Code']
---
Large reasoning language models such as OpenAI-o1 and Deepseek-R1 have recently attracted widespread attention due to their impressive task-solving abilities. However, the enormous model size and the generation of lengthy thought chains introduce significant reasoning costs and response latency. Existing methods for efficient reasoning mainly focus on reducing the number of model parameters or shortening the chain-of-thought length. In this paper, we introduce Speculative Chain-of-Thought (SCoT), which reduces reasoning latency from another perspective by accelerated average reasoning speed through large and small model collaboration. SCoT conducts thought-level drafting using a lightweight draft model. Then it selects the best CoT draft and corrects the error cases with the target model. The proposed thinking behavior alignment improves the efficiency of drafting and the draft selection strategy maintains the prediction accuracy of the target model for complex tasks. Experimental results on GSM8K, MATH, GaoKao, CollegeMath and Olympiad datasets show that SCoT reduces reasoning latency by 48%\\(\sim\\)66% and 21%\\(\sim\\)49% for Deepseek-R1-Distill-Qwen-32B and Deepseek-R1-Distill-Llama-70B while achieving near-target-model-level performance. Our code is available at https://github.com/Jikai0Wang/Speculative_CoT.
