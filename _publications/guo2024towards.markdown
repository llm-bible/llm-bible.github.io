---
layout: publication
title: Stabletoolbench\: Towards Stable Large-scale Benchmarking On Tool Learning Of Large Language Models
authors: Guo Zhicheng, Cheng Sijie, Wang Hao, Liang Shihao, Qin Yujia, Li Peng, Liu Zhiyuan, Sun Maosong, Liu Yang
conference: "Arxiv"
year: 2024
bibkey: guo2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.07714"}
tags: ['Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) have witnessed remarkable advancements in recent years prompting the exploration of tool learning which integrates LLMs with external tools to address diverse real-world challenges. Assessing the capability of LLMs to utilise tools necessitates large-scale and stable benchmarks. However previous works relied on either hand-crafted online tools with limited scale or large-scale real online APIs suffering from instability of API status. To address this problem we introduce StableToolBench a benchmark evolving from ToolBench proposing a virtual API server and stable evaluation system. The virtual API server contains a caching system and API simulators which are complementary to alleviate the change in API status. Meanwhile the stable evaluation system designs solvable pass and win rates using GPT-4 as the automatic evaluator to eliminate the randomness during evaluation. Experimental results demonstrate the stability of StableToolBench and further discuss the effectiveness of API simulators the caching system and the evaluator system.
