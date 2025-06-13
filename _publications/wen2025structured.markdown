---
layout: publication
title: 'SARI: Structured Audio Reasoning Via Curriculum-guided Reinforcement Learning'
authors: Cheng Wen, Tingwei Guo, Shuaijiang Zhao, Wei Zou, Xiangang Li
conference: "Arxiv"
year: 2025
bibkey: wen2025structured
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.15900"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Tools', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Recent work shows that reinforcement learning(RL) can markedly sharpen the
reasoning ability of large language models (LLMs) by prompting them to "think
before answering." Yet whether and how these gains transfer to audio-language
reasoning remains largely unexplored. We extend the Group-Relative Policy
Optimization (GRPO) framework from DeepSeek-R1 to a Large Audio-Language Model
(LALM), and construct a 32k sample multiple-choice corpus. Using a two-stage
regimen supervised fine-tuning on structured and unstructured
chains-of-thought, followed by curriculum-guided GRPO, we systematically
compare implicit vs. explicit, and structured vs. free form reasoning under
identical architectures. Our structured audio reasoning model, SARI (Structured
Audio Reasoning via Curriculum-Guided Reinforcement Learning), achieves a
16.35% improvement in average accuracy over the base model
Qwen2-Audio-7B-Instruct. Furthermore, the variant built upon Qwen2.5-Omni
reaches state-of-the-art performance of 67.08% on the MMAU test-mini benchmark.
Ablation experiments show that on the base model we use: (i) SFT warm-up is
important for stable RL training, (ii) structured chains yield more robust
generalization than unstructured ones, and (iii) easy-to-hard curricula
accelerate convergence and improve final performance. These findings
demonstrate that explicit, structured reasoning and curriculum learning
substantially enhances audio-language understanding.
