---
layout: publication
title: Rewritelm\: An Instruction-tuned Large Language Model For Text Rewriting
authors: Shu Lei, Luo Liangchen, Hoskere Jayakumar, Zhu Yun, Liu Yinxiao, Tong Simon, Chen Jindong, Meng Lei
conference: "AAAI"
year: 2023
bibkey: shu2023instruction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15685"}
  - {name: "Code", url: "https://github.com/google-research/google-research/tree/master/rewritelm)"}
tags: ['Agentic', 'Has Code', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated impressive capabilities in creative tasks such as storytelling and E-mail generation. However as LLMs are primarily trained on final text results rather than intermediate revisions it might be challenging for them to perform text rewriting tasks. Most studies in the rewriting tasks focus on a particular transformation type within the boundaries of single sentences. In this work we develop new strategies for instruction tuning and reinforcement learning to better align LLMs for cross-sentence rewriting tasks using diverse wording and structures expressed through natural languages including 1) generating rewriting instruction data from Wiki edits and public corpus through instruction generation and chain-of-thought prompting; 2) collecting comparison data for reward model training through a new ranking function. To facilitate this research we introduce OpenRewriteEval a novel benchmark covers a wide variety of rewriting types expressed through natural language instructions. Our results show significant improvements over a variety of baselines. The public repository is available on GitHub under Google Research (https://github.com/google-research/google-research/tree/master/rewritelm)."
