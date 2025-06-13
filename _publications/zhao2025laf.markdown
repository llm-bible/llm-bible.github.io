---
layout: publication
title: 'Laf-grpo: In-situ Navigation Instruction Generation For The Visually Impaired Via GRPO With Llm-as-follower Reward'
authors: Yi Zhao, Siqi Wang, Jing Li
conference: "Arxiv"
year: 2025
bibkey: zhao2025laf
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04070"}
  - {name: "Code", url: "https://github.com/YiyiyiZhao/NIG4VI}{https://github.com/YiyiyiZhao/NIG4VI"}
tags: ['Fine-Tuning', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Multimodal Models']
---
Navigation instruction generation for visually impaired (VI) individuals (NIG-VI) is critical yet relatively underexplored. This study, hence, focuses on producing precise, in-situ, step-by-step navigation instructions that are practically usable by VI users. Concretely, we propose LaF-GRPO (LLM-as-Follower GRPO), where an LLM simulates VI user responses to generate rewards guiding the Vision-Language Model (VLM) post-training. This enhances instruction usability while reducing costly real-world data needs. To facilitate training and testing, we introduce NIG4VI, a 27k-sample open-sourced benchmark. It provides diverse navigation scenarios with accurate spatial coordinates, supporting detailed, open-ended in-situ instruction generation. Experiments on NIG4VI show the effectiveness of LaF-GRPO by quantitative metrics (e.g., Zero-(LaF-GRPO) boosts BLEU +14%; SFT+(LaF-GRPO) METEOR 0.542 vs. GPT-4o's 0.323) and yields more intuitive, safer instructions. Code and benchmark are available at \href\{https://github.com/YiyiyiZhao/NIG4VI\}\{https://github.com/YiyiyiZhao/NIG4VI\}.
