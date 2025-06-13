---
layout: publication
title: 'Hierarchical Prompt Decision Transformer: Improving Few-shot Policy Generalization With Global And Adaptive Guidance'
authors: Zhe Wang, Haozhu Wang, Yanjun Qi
conference: "Arxiv"
year: 2024
bibkey: wang2024hierarchical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.00979'}
tags: ['Agentic', 'Transformer', 'Few-Shot', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Decision transformers recast reinforcement learning as a conditional sequence
generation problem, offering a simple but effective alternative to traditional
value or policy-based methods. A recent key development in this area is the
integration of prompting in decision transformers to facilitate few-shot policy
generalization. However, current methods mainly use static prompt segments to
guide rollouts, limiting their ability to provide context-specific guidance.
Addressing this, we introduce a hierarchical prompting approach enabled by
retrieval augmentation. Our method learns two layers of soft tokens as guiding
prompts: (1) global tokens encapsulating task-level information about
trajectories, and (2) adaptive tokens that deliver focused, timestep-specific
instructions. The adaptive tokens are dynamically retrieved from a curated set
of demonstration segments, ensuring context-aware guidance. Experiments across
seven benchmark tasks in the MuJoCo and MetaWorld environments demonstrate the
proposed approach consistently outperforms all baseline methods, suggesting
that hierarchical prompting for decision transformers is an effective strategy
to enable few-shot policy generalization.
