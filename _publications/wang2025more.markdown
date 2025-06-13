---
layout: publication
title: 'More Is Less: The Pitfalls Of Multi-model Synthetic Preference Data In DPO Safety Alignment'
authors: Yifan Wang, Runjin Chen, Bolian Li, David Cho, Yihe Deng, Ruqi Zhang, Tianlong Chen, Zhangyang Wang, Ananth Grama, Junyuan Hong
conference: "Arxiv"
year: 2025
bibkey: wang2025more
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02193"}
tags: ['Responsible AI', 'Agentic', 'GPT', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Prompting']
---
Aligning large language models (LLMs) with human values is an increasingly
critical step in post-training. Direct Preference Optimization (DPO) has
emerged as a simple, yet effective alternative to reinforcement learning from
human feedback (RLHF). Synthetic preference data with its low cost and high
quality enable effective alignment through single- or multi-model generated
preference data. Our study reveals a striking, safety-specific phenomenon
associated with DPO alignment: Although multi-model generated data enhances
performance on general tasks (ARC, Hellaswag, MMLU, TruthfulQA, Winogrande) by
providing diverse responses, it also tends to facilitate reward hacking during
training. This can lead to a high attack success rate (ASR) when models
encounter jailbreaking prompts. The issue is particularly pronounced when
employing stronger models like GPT-4o or larger models in the same family to
generate chosen responses paired with target model self-generated rejected
responses, resulting in dramatically poorer safety outcomes. Furthermore, with
respect to safety, using solely self-generated responses (single-model
generation) for both chosen and rejected pairs significantly outperforms
configurations that incorporate responses from stronger models, whether used
directly as chosen data or as part of a multi-model response pool. We
demonstrate that multi-model preference data exhibits high linear separability
between chosen and rejected responses, which allows models to exploit
superficial cues rather than internalizing robust safety constraints. Our
experiments, conducted on models from the Llama, Mistral, and Qwen families,
consistently validate these findings.
