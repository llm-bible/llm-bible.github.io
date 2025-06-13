---
layout: publication
title: 'Dynamic Compressing Prompts For Efficient Inference Of Large Language Models'
authors: Jinwu Hu, Wei Zhang, Yufeng Wang, Yu Hu, Bin Xiao, Mingkui Tan, Qing Du
conference: "Arxiv"
year: 2025
bibkey: hu2025dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11004"}
  - {name: "Code", url: "https://github.com/Fhujinwu/DCP"}
tags: ['Agentic', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Prompting']
---
Large Language Models (LLMs) have shown outstanding performance across a
variety of tasks, partly due to advanced prompting techniques. However, these
techniques often require lengthy prompts, which increase computational costs
and can hinder performance because of the limited context windows of LLMs.
While prompt compression is a straightforward solution, existing methods
confront the challenges of retaining essential information, adapting to context
changes, and remaining effective across different tasks. To tackle these
issues, we propose a task-agnostic method called Dynamic Compressing Prompts
(LLM-DCP). Our method reduces the number of prompt tokens while aiming to
preserve the performance as much as possible. We model prompt compression as a
Markov Decision Process (MDP), enabling the DCP-Agent to sequentially remove
redundant tokens by adapting to dynamic contexts and retaining crucial content.
We develop a reward function for training the DCP-Agent that balances the
compression rate, the quality of the LLM output, and the retention of key
information. This allows for prompt token reduction without needing an external
black-box LLM. Inspired by the progressive difficulty adjustment in curriculum
learning, we introduce a Hierarchical Prompt Compression (HPC) training
strategy that gradually increases the compression difficulty, enabling the
DCP-Agent to learn an effective compression method that maintains information
integrity. Experiments demonstrate that our method outperforms state-of-the-art
techniques, especially at higher compression rates. The code for our approach
will be available at https://github.com/Fhujinwu/DCP.
