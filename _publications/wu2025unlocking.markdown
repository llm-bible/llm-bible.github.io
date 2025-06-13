---
layout: publication
title: 'Unlocking Efficient Long-to-short LLM Reasoning With Model Merging'
authors: Han Wu, Yuxuan Yao, Shuqi Liu, Zehua Liu, Xiaojin Fu, Xiongwei Han, Xing Li, Hui-ling Zhen, Tao Zhong, Mingxuan Yuan
conference: "Arxiv"
year: 2025
bibkey: wu2025unlocking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.20641"}
  - {name: "Code", url: "https://github.com/hahahawu/Long-to-Short-via-Model-Merging"}
tags: ['Agentic', 'Security', 'Training Techniques', 'Efficiency and Optimization', 'Reinforcement Learning', 'RAG', 'Merging', 'Pretraining Methods', 'Fine-Tuning', 'Has Code', 'Prompting']
---
The transition from System 1 to System 2 reasoning in large language models (LLMs) has marked significant advancements in handling complex tasks through deliberate, iterative thinking. However, this progress often comes at the cost of efficiency, as models tend to overthink, generating redundant reasoning steps without proportional improvements in output quality. Long-to-Short (L2S) reasoning has emerged as a promising solution to this challenge, aiming to balance reasoning depth with practical efficiency. While existing approaches, such as supervised fine-tuning (SFT), reinforcement learning (RL), and prompt engineering, have shown potential, they are either computationally expensive or unstable. Model merging, on the other hand, offers a cost-effective and robust alternative by integrating the quick-thinking capabilities of System 1 models with the methodical reasoning of System 2 models. In this work, we present a comprehensive empirical study on model merging for L2S reasoning, exploring diverse methodologies, including task-vector-based, SVD-based, and activation-informed merging. Our experiments reveal that model merging can reduce average response length by up to 55% while preserving or even improving baseline performance. We also identify a strong correlation between model scale and merging efficacy with extensive evaluations on 1.5B/7B/14B/32B models. Furthermore, we investigate the merged model's ability to self-critique and self-correct, as well as its adaptive response length based on task complexity. Our findings highlight model merging as a highly efficient and effective paradigm for L2S reasoning, offering a practical solution to the overthinking problem while maintaining the robustness of System 2 reasoning. This work can be found on Github https://github.com/hahahawu/Long-to-Short-via-Model-Merging.
