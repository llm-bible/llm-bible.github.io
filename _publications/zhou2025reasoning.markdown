---
layout: publication
title: 'Reasoning Like An Economist: Post-training On Economic Problems Induces Strategic Generalization In Llms'
authors: Yufa Zhou, Shaobo Wang, Xingyu Dong, Xiangqi Jin, Yifang Chen, Yue Min, Kexin Yang, Xingzhang Ren, Dayiheng Liu, Linfeng Zhang
conference: "Arxiv"
year: 2025
bibkey: zhou2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00577"}
  - {name: "Code", url: "https://github.com/MasterZhou1/Recon"}
tags: ['Fine-Tuning', 'Agentic', 'Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Agent', 'Has Code', 'Pretraining Methods']
---
Directly training Large Language Models (LLMs) for Multi-Agent Systems (MAS) remains challenging due to intricate reward modeling, dynamic agent interactions, and demanding generalization requirements. This paper explores whether post-training techniques, specifically Supervised Fine-Tuning (SFT) and Reinforcement Learning with Verifiable Rewards (RLVR), can effectively \\(\textit\{generalize\}\\) to multi-agent scenarios. We use economic reasoning as a testbed, leveraging its strong foundations in mathematics and game theory, its demand for structured analytical reasoning, and its relevance to real-world applications such as market design, resource allocation, and policy analysis. We introduce \\(\textbf\{Recon\}\\) (\\(\textbf\{R\}\\)easoning like an \\(\textbf\{ECON\}\\)omist), a 7B-parameter open-source LLM post-trained on a hand-curated dataset of 2,100 high-quality economic reasoning problems. Comprehensive evaluation on economic reasoning benchmarks and multi-agent games reveals clear improvements in structured reasoning and economic rationality. These results underscore the promise of domain-aligned post-training for enhancing reasoning and agent alignment, shedding light on the roles of SFT and RL in shaping model behavior. Code is available at https://github.com/MasterZhou1/Recon .
