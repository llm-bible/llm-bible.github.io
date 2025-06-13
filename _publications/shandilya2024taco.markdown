---
layout: publication
title: 'TACO-RL: Task Aware Prompt Compression Optimization With Reinforcement Learning'
authors: Shivam Shandilya, Menglin Xia, Supriyo Ghosh, Huiqiang Jiang, Jue Zhang, Qianhui Wu, Victor Rühle
conference: "Arxiv"
year: 2024
bibkey: shandilya2024taco
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.13035"}
tags: ['Agentic', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Pretraining Methods', 'Transformer', 'Prompting', 'Applications']
---
The increasing prevalence of large language models (LLMs) such as GPT-4 in
various applications has led to a surge in the size of prompts required for
optimal performance, leading to challenges in computational efficiency. Prompt
compression aims to reduce the inference cost by minimizing input tokens
without compromising on the task performance. However, existing prompt
compression techniques either rely on sub-optimal metrics such as information
entropy or model it as a task-agnostic token classification problem that fails
to capture task-specific information. To address these issues, we propose a
novel and efficient reinforcement learning (RL) based task-aware prompt
compression method. To ensure low latency requirements, we leverage existing
Transformer encoder-based token classification model while guiding the learning
process with task-specific reward signals using lightweight REINFORCE
algorithm. We evaluate the performance of our method on three diverse and
challenging tasks including text summarization, question answering and code
summarization. We demonstrate that our RL-guided compression method improves
the task performance by 8% - 189% across these three scenarios over
state-of-the-art compression techniques while satisfying the same compression
rate and latency requirements.
