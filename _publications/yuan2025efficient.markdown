---
layout: publication
title: 'Efficient RL Training For Reasoning Models Via Length-aware Optimization'
authors: Danlong Yuan, Tian Xie, Shaohan Huang, Zhuocheng Gong, Huishuai Zhang, Chong Luo, Furu Wei, Dongyan Zhao
conference: "Arxiv"
year: 2025
bibkey: yuan2025efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12284"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RAG']
---
Large reasoning models, such as OpenAI o1 or DeepSeek R1, have demonstrated remarkable performance on reasoning tasks but often incur a long reasoning path with significant memory and time costs. Existing methods primarily aim to shorten reasoning paths by introducing additional training data and stages. In this paper, we propose three critical reward designs integrated directly into the reinforcement learning process of large reasoning models, which reduce the response length without extra training stages. Experiments on four settings show that our method significantly decreases response length while maintaining or even improving performance. Specifically, in a logic reasoning setting, we achieve a 40% reduction in response length averaged by steps alongside a 14% gain in performance. For math problems, we reduce response length averaged by steps by 33% while preserving performance.
