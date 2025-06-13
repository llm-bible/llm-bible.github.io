---
layout: publication
title: 'Advancing Tool-augmented Large Language Models Via Meta-verification And Reflection Learning'
authors: Zhiyuan Ma, Jiayu Liu, Xianzhen Luo, Zhenya Huang, Qingfu Zhu, Wanxiang Che
conference: "Arxiv"
year: 2025
bibkey: ma2025advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04625"}
tags: ['Fine-Tuning', 'Agentic', 'GPT', 'Tools', 'RAG', 'Model Architecture']
---
Empowering large language models (LLMs) with effective tool utilization capabilities is crucial for enabling AI agents to solve complex problems. However, current models face two major limitations: (1) unreliable tool planning and invocation due to low-quality instruction datasets (e.g., widespread hallucinated API calls), and (2) weak tool reflection abilities (over 90% of errors cannot be corrected) resulting from static imitation learning. To address these critical limitations, we propose Tool-MVR, a novel Tool-Augmented LLM that achieves comprehensive System 2 reasoning through two key innovations. Specifically, we first introduce Multi-Agent Meta-Verification (MAMV), a systematic pipeline that rigorously validates APIs, queries, and reasoning trajectories to construct ToolBench-V, a new high-quality instruction dataset that addresses the limitation of unreliable tool planning and invocation. Second, we propose Exploration-based Reflection Learning (EXPLORE), which enhances tool reflection capabilities by leveraging tool feedback through a dynamic "Error -> Reflection -> Correction" learning paradigm, resulting in our reflection dataset ToolBench-R and addressing the critical weakness in tool reflection. Finally, we obtain Tool-MVR by finetuning open-source LLMs (e.g., Qwen-7B) on both ToolBench-V and ToolBench-R. Our experiments demonstrate that Tool-MVR achieves state-of-the-art performance on StableToolBench, surpassing both ToolLLM (by 23.9%) and GPT-4 (by 15.3%) while reducing API calls by 31.4%, with strong generalization capabilities across unseen tools and scenarios. Additionally, on our proposed RefineToolBench, the first benchmark specifically designed to evaluate tool reflection capabilities, Tool-MVR achieves a 58.9% error correction rate, significantly outperforming ToolLLM's 9.1%.
