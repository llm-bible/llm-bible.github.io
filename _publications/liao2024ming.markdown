---
layout: publication
title: 'MING-MOE: Enhancing Medical Multi-task Learning In Large Language Models With Sparse Mixture Of Low-rank Adapter Experts'
authors: Liao Yusheng, Jiang Shuyang, Wang Yu, Wang Yanfeng
conference: "Arxiv"
year: 2024
bibkey: liao2024ming
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.09027"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Uncategorized']
---
Large language models like ChatGPT have shown substantial progress in natural
language understanding and generation, proving valuable across various
disciplines, including the medical field. Despite advancements, challenges
persist due to the complexity and diversity inherent in medical tasks which
often require multi-task learning capabilities. Previous approaches, although
beneficial, fall short in real-world applications because they necessitate
task-specific annotations at inference time, limiting broader generalization.
This paper introduces MING-MOE, a novel Mixture-of-Expert~(MOE)-based medical
large language model designed to manage diverse and complex medical tasks
without requiring task-specific annotations, thus enhancing its usability
across extensive datasets. MING-MOE employs a Mixture of Low-Rank Adaptation
(MoLoRA) technique, allowing for efficient parameter usage by maintaining base
model parameters static while adapting through a minimal set of trainable
parameters. We demonstrate that MING-MOE achieves state-of-the-art (SOTA)
performance on over 20 medical tasks, illustrating a significant improvement
over existing models. This approach not only extends the capabilities of
medical language models but also improves inference efficiency.
