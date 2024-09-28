---
layout: publication
title: P2DT Mitigating Forgetting in task-incremental Learning with progressive prompt Decision Transformer
authors: Wang Zhiyuan, Qu Xiaoyang, Xiao Jing, Chen Bokui, Wang Jianzong
conference: "Arxiv"
year: 2024
bibkey: wang2024p2dt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.11666"}
tags: ['Model Architecture', 'Transformer', 'Arxiv']
---
Catastrophic forgetting poses a substantial challenge for managing intelligent agents controlled by a large model causing performance degradation when these agents face new tasks. In our work we propose a novel solution - the Progressive Prompt Decision Transformer (P2DT). This method enhances a transformer-based model by dynamically appending decision tokens during new task training thus fostering task-specific policies. Our approach mitigates forgetting in continual and offline reinforcement learning scenarios. Moreover P2DT leverages trajectories collected via traditional reinforcement learning from all tasks and generates new task-specific tokens during training thereby retaining knowledge from previous studies. Preliminary results demonstrate that our model effectively alleviates catastrophic forgetting and scales well with increasing task environments.
